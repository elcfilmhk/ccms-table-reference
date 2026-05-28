# `FKK_SEC_N`

**Description:** Security Deposit Notice — security notice records
**Category:** Standard SAP Table
**References:** 34 SELECT statements across 19 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `VKONT` | | 🔑 | Primary key |
| `SECID` | | 🔑 | Primary key |

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
