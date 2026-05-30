# `DFKKCFRLS`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 7 SELECT statements across 7 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dfkkcfrls/) — validated 2026-05-30, schema v1.0
**Schema fields:** 24 fields | **Data types:** CHAR(14), CUKY(2), CURR(2), DATS(5), INT1(1)

## Key Fields
`BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `SELT1` | SELTX_KK | TFK004 | CHAR | 1 | 0 | Selection Category |
| `SELW1` | SELOP_KK | — | CHAR | 20 | 0 | Field value to be selected |
| `BETRR` | BETRR_KK | — | CURR | 13 | 2 | Return amount |
| `BETRU` | BETRU_KK | — | CURR | 13 | 2 | Input Amount For Returns in Transaction Currency |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `WAERSU` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `BUDAT` | BUDAT_KK | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `VALUT` | VALUT | — | DATS | 8 | 0 | Value date |
| `FIKEY` | FIKEY_KK | DFKKSUMC | CHAR | 12 | 0 | Reconciliation Key for General Ledger |
| `RLSKO` | RLSKO_KK | SKB1 | CHAR | 10 | 0 | Bank clearing account for returns |
| `RLGRD` | RLGRD_KK | TFK045A | CHAR | 3 | 0 | Return reason |
| `RLHBK` | RLHBK_KK | TFK045D | CHAR | 6 | 0 | House bank&#039;s return reason |
| `OPBEL` | OPZBEL_KK | — | CHAR | 12 | 0 | Payment document for returns |
| `TXTVW` | TXTVW_KK | — | CHAR | 80 | 0 | Note to Payee in Payment |
| `KLAEB` | KLAEB_KK | — | CHAR | 12 | 0 | Number of Clarification Document |
| `STATE` | CFC_STATE | CFC_ITEM_STATE | CHAR | 2 | 0 | CFC: Status of an application table entry |
| `LOCK_USER` | CFC_UNAME | — | CHAR | 12 | 0 | Name of the person to last change the status of the object |
| `LOCK_LIMIT` | CFC_LOCK_LIMIT | — | DATS | 8 | 0 | CFC: Lock period of a lock entry |
| `WORKSTATE` | CFC_WORKSTATE | CFC_IT_WORKSTATE | CHAR | 2 | 0 | Last processing status of a clarification case |
| `RESUBMIT_DATE` | CFC_RESUBMIT_DATE | — | DATS | 8 | 0 | Date on which Resubmission Occurs |
| `WF_COUNT` | CFC_WORKFLOW_COUNTER | — | INT1 | 3 | 0 | Number of active workflows with this clarification case |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BUKRS` | DFKKCFRLS | MANDT | T001 |  | |
| `BUKRS` | DFKKCFRLS | BUKRS | T001 |  | |
| `FIKEY` | DFKKCFRLS | MANDT | DFKKSUMC |  | |
| `FIKEY` | DFKKCFRLS | FIKEY | DFKKSUMC |  | |
| `GSBER` | DFKKCFRLS | MANDT | TGSB |  | |
| `GSBER` | DFKKCFRLS | GSBER | TGSB |  | |
| `RLGRD` | * |  | TFK045A |  | |
| `RLGRD` | DFKKCFRLS | MANDT | TFK045A |  | |
| `RLGRD` | DFKKCFRLS | RLGRD | TFK045A |  | |
| `RLHBK` | DFKKCFRLS | MANDT | TFK045D |  | |
| `RLHBK` | DFKKCFRLS | BUKRS | TFK045D |  | |
| `RLHBK` | T012 | HBKID | TFK045D |  | |
| `RLHBK` | DFKKCFRLS | RLHBK | TFK045D |  | |
| `RLSKO` | DFKKCFRLS | MANDT | SKB1 |  | |
| `RLSKO` | DFKKCFRLS | BUKRS | SKB1 |  | |
| `RLSKO` | DFKKCFRLS | RLSKO | SKB1 |  | |
| `SELT1` | DFKKCFRLS | MANDT | TFK004 |  | |
| `SELT1` | * |  | TFK004 |  | |
| `SELT1` | DFKKCFRLS | SELT1 | TFK004 |  | |
| `STATE` | SY | MANDT | CFC_ITEM_STATE |  | |
| `STATE` | * |  | CFC_ITEM_STATE |  | |
| `STATE` | DFKKCFRLS | STATE | CFC_ITEM_STATE |  | |
| `WAERS` | DFKKCFRLS | MANDT | TCURC |  | |
| `WAERS` | DFKKCFRLS | WAERS | TCURC |  | |
| `WAERSU` | DFKKCFRLS | WAERSU | TCURC |  | |
| `WAERSU` | DFKKCFRLS | MANDT | TCURC |  | |
| `WORKSTATE` | SY | MANDT | CFC_IT_WORKSTATE |  | |
| `WORKSTATE` | * |  | CFC_IT_WORKSTATE |  | |
| `WORKSTATE` | DFKKCFRLS | WORKSTATE | CFC_IT_WORKSTATE |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisfi0046.txt`
- `zisfi0103.txt`
- `zisfi0116.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test.txt`
- `zisfi0116_test2.txt`
- `zisfi0116_test3.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_