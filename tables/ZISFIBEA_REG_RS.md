# ZISFIBEA_REG_RS
**Description:** BEA Reject Reason Code Master
**Total Fields:** 5
**Key Fields:** MANDT, REASON_CODE, VALID_FROM, VALID_TO

## Programs Using This Table
- `zisfi0254`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REASON_CODE` | NUMC | 3 | 🔑 | Reject Reason Code |
| 3 | `VALID_FROM` | DATS | 8 | 🔑 | Valid from |
| 4 | `VALID_TO` | DATS | 8 | 🔑 | Valid to |
| 5 | `REASON` | CHAR | 255 |  | Reject Reason |
