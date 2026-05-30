# `FKK_SEC_N`

**Description:** Security Deposit Notice — security notice records
**Category:** Standard SAP Table
**References:** 34 SELECT statements across 19 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkk_sec_n/) — validated 2026-05-30, schema v1.0
**Schema fields:** 7 fields | **Data types:** CHAR(5), DATS(1), NUMC(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `NC_STATUS` | NC_STATUS_KK | TFK_SEC_STATUS | NUMC | 2 | 0 | Noncash security deposit status |
| `TYP` | TYP_KK | TFK_SEC_TYPE | CHAR | 4 | 0 | Noncash security deposit category |
| `REFNO` | REFNO_KK | — | CHAR | 40 | 0 | Reference number for non-cash security deposit |
| `GPART_GUARANTOR` | GPART_GUARANTOR_KK | BUT000 | CHAR | 10 | 0 | Guarantor of a noncash security deposit |
| `XBUPP` | XBUPP_KK | — | CHAR | 1 | 0 | Indicator: Guarantor is a Private Person |
| `VKONT_GUARANTOR` | VKONT_KK | FKKVK | CHAR | 12 | 0 | Contract Account Number |
| `SEC_EXPIRE` | SEC_EXPIRE_KK | — | DATS | 8 | 0 | Expiration date of noncash security deposit |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `GPART_GUARANTOR` | SYST | MANDT | BUT000 |  | |
| `GPART_GUARANTOR` | FKK_SEC_N | GPART_GUARANTOR | BUT000 |  | |
| `MANDT` | FKK_SEC_N | MANDT | T000 |  | |
| `NC_STATUS` | SYST | MANDT | TFK_SEC_STATUS |  | |
| `NC_STATUS` | FKK_SEC_N | NC_STATUS | TFK_SEC_STATUS |  | |
| `SECURITY` | FKK_SEC_N | MANDT | FKK_SEC |  | |
| `SECURITY` | FKK_SEC_N | SECURITY | FKK_SEC |  | |
| `TYP` | SYST | MANDT | TFK_SEC_TYPE |  | |
| `TYP` | FKK_SEC_N | TYP | TFK_SEC_TYPE |  | |
| `VKONT_GUARANTOR` | SYST | MANDT | FKKVK |  | |
| `VKONT_GUARANTOR` | FKK_SEC_N | VKONT_GUARANTOR | FKKVK |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `NC_STATUS`, `REFNO`, `SECURITY`, `SEC_EXPIRE`, `TYP`, `nc_status`, `security`, `typ`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `NC_STATUS`, `nc_status`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_calculate_deposit.txt`
- `z_get_security_deposit.txt`
- `ziscs0088.txt`
- `zisfi0025.txt`
- `zisfi0036.txt`
- `zisfi0037.txt`
- `zisfi0038.txt`
- `zisfi0045.txt`
- `zisfi0051.txt`
- `zisfi0052.txt`
- `zisfi0058.txt`
- `zisfi0060.txt`
- `zisfi0113_upd.txt`
- `zisfi0138.txt`
- `zisfi0159.txt`
- `zisfi0202.txt`
- `zisfi0203.txt`
- `zisfi0231.txt`
- `zisfi0285.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_