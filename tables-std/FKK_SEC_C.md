# `FKK_SEC_C`

**Description:** Security Deposit Cancel — cancelled security
**Category:** Standard SAP Table
**References:** 30 SELECT statements across 17 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VKONT` | | 🔑 | Primary key |
| `SECID` | | 🔑 | Primary key |

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
