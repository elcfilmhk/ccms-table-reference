# ZISCSPROMPLAN_G
**Description:** Promotion planning (Generic)
**Total Fields:** 15
**Key Fields:** MANDT, PROMONAME

## Programs Using This Table
- `ziscs0164`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMONAME` | CHAR | 10 | 🔑 | Promotion activity name |
| 3 | `PROMODESC` | CHAR | 80 |  | Description of promotion activity |
| 4 | `PROMOSTART` | DATS | 8 |  | Start date of promotion activity |
| 5 | `PROMOEND` | DATS | 8 |  | End date of promotion activity |
| 6 | `PROMPRIOR` | CHAR | 1 |  | Priority of promotion activity |
| 7 | `PROMOUSER` | CHAR | 12 |  | Responsible person user ID |
| 8 | `PROMOSCRIPT1` | CHAR | 100 |  | Scripting |
| 9 | `PROMOSCRIPT2` | CHAR | 100 |  | Scripting |
| 10 | `PROMOSCRIPT3` | CHAR | 100 |  | Scripting |
| 11 | `PROMOSCRIPT4` | CHAR | 100 |  | Scripting |
| 12 | `PROMOSCRIPT5` | CHAR | 100 |  | Scripting |
| 13 | `PROMOSCRIPT6` | CHAR | 100 |  | Scripting |
| 14 | `PROMOSCRIPT7` | CHAR | 100 |  | Scripting |
| 15 | `PROMOSCRIPT8` | CHAR | 100 |  | Scripting |
