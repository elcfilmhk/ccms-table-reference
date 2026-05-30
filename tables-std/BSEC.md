# `BSEC`

**Description:** SAP standard table
**Category:** Standard SAP Table
**References:** 1 SELECT statements across 1 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/bsec/) — validated 2026-05-30, schema v1.0
**Schema fields:** 38 fields | **Data types:** CHAR(37), LANG(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `NAME1` | NAME1_GP | — | CHAR | 35 | 0 | Name 1 |
| `NAME2` | NAME2_GP | — | CHAR | 35 | 0 | Name 2 |
| `NAME3` | NAME3_GP | — | CHAR | 35 | 0 | Name 3 |
| `NAME4` | NAME4_GP | — | CHAR | 35 | 0 | Name 4 |
| `PSTLZ` | PSTLZ | — | CHAR | 10 | 0 | Postal Code |
| `ORT01` | ORT01_GP | — | CHAR | 35 | 0 | City |
| `LAND1` | LAND1_GP | T005 | CHAR | 3 | 0 | Country Key |
| `STRAS` | STRAS_GP | — | CHAR | 35 | 0 | House number and street |
| `PFACH` | PFACH | — | CHAR | 10 | 0 | PO Box |
| `PSTL2` | PSTL2 | — | CHAR | 10 | 0 | P.O. Box Postal Code |
| `PSKTO` | PSKTO | — | CHAR | 16 | 0 | Account Number of Bank Account At Post Office |
| `BANKN` | BANKN | — | CHAR | 18 | 0 | Bank account number |
| `BANKL` | BANKK | — | CHAR | 15 | 0 | Bank Keys |
| `BANKS` | BANKS | T005 | CHAR | 3 | 0 | Bank country key |
| `STCD1` | STCD1 | — | CHAR | 16 | 0 | Tax Number 1 |
| `STCD2` | STCD2 | — | CHAR | 11 | 0 | Tax Number 2 |
| `STKZU` | STKZU | — | CHAR | 1 | 0 | Liable for VAT |
| `STKZA` | STKZA | — | CHAR | 1 | 0 | Indicator: Business Partner Subject to Equalization Tax? |
| `REGIO` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `BKONT` | BKONT | — | CHAR | 2 | 0 | Bank Control Key |
| `DTAWS` | DTAWS | — | CHAR | 2 | 0 | Instruction key for data medium exchange |
| `DTAMS` | DTAMS | — | CHAR | 1 | 0 | Indicator for Data Medium Exchange |
| `XCPDK` | XCPDK | — | CHAR | 1 | 0 | Indicator: Is the account a one-time account? |
| `EMPFG` | EMPFG | — | CHAR | 16 | 0 | Payee code |
| `SPRAS` | SPRAS | T002 | LANG | 1 | 0 | Language Key |
| `FITYP` | J_1AFITP_D | J_1AFITP | CHAR | 2 | 0 | Tax type |
| `STCDT` | J_1ATOID | J_1ATODC | CHAR | 2 | 0 | Tax Number Type |
| `STKZN` | STKZN | — | CHAR | 1 | 0 | Natural Person |
| `STCD3` | STCD3 | — | CHAR | 18 | 0 | Tax Number 3 |
| `STCD4` | STCD4 | — | CHAR | 18 | 0 | Tax Number 4 |
| `BKREF` | BKREF | — | CHAR | 20 | 0 | Reference specifications for bank details |
| `J_1KFREPRE` | REPRES | — | CHAR | 10 | 0 | Name of Representative |
| `J_1KFTBUS` | GESTYP | BUSTYPE | CHAR | 30 | 0 | Type of Business |
| `J_1KFTIND` | INDTYP | INDUSTYPE | CHAR | 30 | 0 | Type of Industry |
| `ANRED` | ANRED | — | CHAR | 15 | 0 | Title |
| `ADRNR` | ADRNR | — | CHAR | 10 | 0 | Address |
| `XRGUH` | XRGUH | — | CHAR | 1 | 0 | Indicator: Bank Details from REGUH |
| `PO_BOX_NUM` | AD_POBXNUM | — | CHAR | 1 | 0 | Flag: PO Box Without Number |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BANKS` | BSEC | MANDT | T005 |  | |
| `BANKS` | BSEC | BANKS | T005 |  | |
| `BUKRS` | BSEC | BUKRS | T001 |  | |
| `BUKRS` | BSEC | MANDT | T001 |  | |
| `FITYP` | BSEC | FITYP | J_1AFITP |  | |
| `FITYP` | BSEC | MANDT | J_1AFITP |  | |
| `FITYP` | BSEG | KOART | J_1AFITP |  | |
| `J_1KFTBUS` | BSEC | MANDT | BUSTYPE |  | |
| `J_1KFTBUS` | BSEC | J_1KFTBUS | BUSTYPE |  | |
| `J_1KFTIND` | BSEC | MANDT | INDUSTYPE |  | |
| `J_1KFTIND` | BSEC | J_1KFTIND | INDUSTYPE |  | |
| `LAND1` | BSEC | LAND1 | T005 |  | |
| `LAND1` | BSEC | MANDT | T005 |  | |
| `MANDT` | BSEC | MANDT | T000 |  | |
| `REGIO` | BSEC | MANDT | T005S |  | |
| `REGIO` | BSEC | LAND1 | T005S |  | |
| `REGIO` | BSEC | REGIO | T005S |  | |
| `SPRAS` | BSEC | SPRAS | T002 |  | |
| `STCDT` | BSEC | MANDT | J_1ATODC |  | |
| `STCDT` | BSEC | STCDT | J_1ATODC |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zfchzuord_2.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_