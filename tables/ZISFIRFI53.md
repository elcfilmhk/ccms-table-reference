# ZISFIRFI53
**Description:** Custom table for consumption sales and growth figure
**Total Fields:** 5
**Key Fields:** MANDT, CLASS

## Programs Using This Table
- `zisbi0071`
- `zisbi0071_tmp`
- `zisfi0083`
- `zisfi0083_1`
- `zisfi0083_1t`
- `zisfi0083_2`
- `zisfi0083_m2`
- `zisfi0083_m2t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CLASS` | CHAR | 4 | 🔑 | Account Class |
| 3 | `CLASSTEXT` | CHAR | 50 |  | Account Class Description |
| 4 | `GROUP1` | CHAR | 50 |  | Regulatory roll-up |
| 5 | `GROUP2` | CHAR | 50 |  | Trade Category roll-up |
