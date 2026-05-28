# ZISFICKRL
**Description:** Custom Table for Checking Rule Dep. Holding & Further Dep.
**Total Fields:** 5
**Key Fields:** MANDT, ZZDEPFROM, ZZDEPTO

## Programs Using This Table
- `zisfi0025`
- `zisfi0045`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZDEPFROM` | CURR | 13 | 🔑 | Currency-dependent amount |
| 3 | `ZZDEPTO` | CURR | 13 | 🔑 | Currency-dependent amount |
| 4 | `ZZFURDEP_AMOUNT` | CURR | 13 |  | Currency-dependent amount |
| 5 | `ZZFURDEP_PERCENT` | INT1 | 3 |  | Data Element for ZZFURDEP_PERCENT |
