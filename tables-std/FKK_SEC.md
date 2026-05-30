# `FKK_SEC`

**Description:** Security Deposit — CA security deposit
**Category:** Standard SAP Table
**References:** 109 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkk_sec/) — validated 2026-05-30, schema v1.0
**Schema fields:** 22 fields | **Data types:** CHAR(17), CUKY(1), DATS(4)

## Key Fields
`VKONT` | `BUKRS`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `NON_CASH` | NON_CASH_KK | — | CHAR | 1 | 0 | Choose: noncash security deposit |
| `REASON` | REASON_KK | TFK_SEC_REASON | CHAR | 4 | 0 | Reason for Requesting a Security Deposit |
| `VKONT` | VKONT_KK | FKKVK | CHAR | 12 | 0 | Contract Account Number |
| `SEC_START` | SEC_START_KK | — | DATS | 8 | 0 | Start date for security deposit |
| `SEC_RETURN` | SEC_RETURN_KK | — | DATS | 8 | 0 | Return date for security deposit |
| `WAERS` | WAERS | TCURC | CUKY | 5 | 0 | Currency Key |
| `OPBEL` | OPBEL_KK | DFKKKO | CHAR | 12 | 0 | Number of Contract Accts Rec. &amp; Payable Doc. |
| `REV_REASON` | REV_REASON_KK | TFK_SEC_REV | CHAR | 4 | 0 | Reversal reason for security deposit |
| `NRZAS` | NRZAS_KK | — | CHAR | 12 | 0 | Payment Form Number |
| `OBJTYPE` | SWO_OBJTYP | TOJTB | CHAR | 10 | 0 | Object Type |
| `OBJKEY` | SEC_OBJTYP_KK | — | CHAR | 70 | 0 | Object Key for Cash Securities |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BRGRU` | BRGRU | — | CHAR | 4 | 0 | Authorization Group |
| `IKEY` | IKEY_KK | TFK056A | CHAR | 2 | 0 | Interest Key |
| `X_SEC_REV` | X_SEC_REV_KK | — | CHAR | 1 | 0 | Security Deposit Reversed |
| `X_SEC_REL` | X_SEC_REL_KK | — | CHAR | 1 | 0 | Security Deposits Released |
| `BUKRS` | BUKRS | — | CHAR | 4 | 0 | Company Code |
| `EXT_REF_NO` | SEC_XRFNR_KK | — | CHAR | 20 | 0 | External Reference Number of Security Deposit |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `IKEY` | SY | MANDT | TFK056A |  | |
| `IKEY` | FKK_SEC | IKEY | TFK056A |  | |
| `MANDT` | FKK_SEC | MANDT | T000 |  | |
| `OBJTYPE` | FKK_SEC | OBJTYPE | TOJTB |  | |
| `OPBEL` | FKK_SEC | MANDT | DFKKKO |  | |
| `OPBEL` | FKK_SEC | OPBEL | DFKKKO |  | |
| `REASON` | FKK_SEC | MANDT | TFK_SEC_REASON |  | |
| `REASON` | FKK_SEC | REASON | TFK_SEC_REASON |  | |
| `REV_REASON` | FKK_SEC | MANDT | TFK_SEC_REV |  | |
| `REV_REASON` | FKK_SEC | REV_REASON | TFK_SEC_REV |  | |
| `VKONT` | FKK_SEC | MANDT | FKKVK |  | |
| `VKONT` | FKK_SEC | VKONT | FKKVK |  | |
| `WAERS` | FKK_SEC | WAERS | TCURC |  | |
| `WAERS` | FKK_SEC | MANDT | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ACC`, `NON_CASH`, `SECURITY`, `VKONT`, `aedat`, `aenam`, `ernam`, `non_cash`, `objkey`, `objtype`, `opbel`, `reason`, `rev_reason`, `sec_return`, `sec_start`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VKONT`, `vkont`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_calculate_deposit.txt`
- `z_isu_event_0830.txt`
- `z_sec_rep_rel.txt`
- `zis_security_deposit.txt`
- `zisbi0030.txt`
- `ziscs_migration_deposit_mock3.txt`
- `zisdatveri.txt`
- `zisfi0010.txt`
- `zisfi0025_corr_print.txt`
- `zisfi0039.txt`
- `zisfi0041.txt`
- `zisfi0052.txt`
- `zisfi0093.txt`
- `zisfi0101.txt`
- `zisfi0132.txt`
- `zisfi0158.txt`
- `zisfi0159.txt`
- `zisfi0165.txt`
- `zisfi0214.txt`
- `zisfi0217.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_