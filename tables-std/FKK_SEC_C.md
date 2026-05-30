# `FKK_SEC_C`

**Description:** Security Deposit Cancel — cancelled security
**Category:** Standard SAP Table
**References:** 30 SELECT statements across 17 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkk_sec_c/) — validated 2026-05-30, schema v1.0
**Schema fields:** 2 fields | **Data types:** CURR(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `REQUEST` | REQUEST_KK | — | CURR | 11 | 2 | Requested Amount for Security Deposit |
| `SEC_TAXES` | SEC_TAX_KK | — | CURR | 11 | 2 | Taxes on Cash Security Deposits |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | FKK_SEC_C | MANDT | T000 |  | |
| `SECURITY` | FKK_SEC_C | MANDT | FKK_SEC |  | |
| `SECURITY` | FKK_SEC_C | SECURITY | FKK_SEC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `REQUEST`, `SECURITY`, `VTREF`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `SECURITY`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `method-check_ca_deposit.txt`
- `z_calculate_deposit.txt`
- `z_get_security_deposit.txt`
- `ziscs0088.txt`
- `ziscs_sms02.txt`
- `zisfi0025.txt`
- `zisfi0037.txt`
- `zisfi0038.txt`
- `zisfi0045.txt`
- `zisfi0052.txt`
- `zisfi0060.txt`
- `zisfi0082.txt`
- `zisfi0093.txt`
- `zisfi0119.txt`
- `zisfi0202.txt`
- `zisfi0231.txt`
- `zisfi0285.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_