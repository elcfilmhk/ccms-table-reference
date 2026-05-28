# ZISCSCSTAT
**Description:** Contract account statistics by Tariff type
**Total Fields:** 11
**Key Fields:** MANDT, RUNDATE, CLASS

## Programs Using This Table
- `ziscs0074`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Date |
| 3 | `CLASS` | CHAR | 2 | 🔑 | Acc. det. ID |
| 4 | `IN_MONTH` | DEC | 15 |  | MI count |
| 5 | `OUT_MONTH` | DEC | 15 |  | MO count |
| 6 | `TOTAL_CONT` | DEC | 15 |  | Total contracts |
| 7 | `IN_MONTH1` | DEC | 15 |  | MI count (w/ device) |
| 8 | `OUT_MONTH1` | DEC | 15 |  | MO count (w/ device) |
| 9 | `TOTAL_CONT1` | DEC | 15 |  | Total contracts (w/ device) |
| 10 | `CREATEDATE` | DATS | 8 |  | Date created |
| 11 | `CREATETIME` | TIMS | 6 |  | Time created |
