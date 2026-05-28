# ZISCSPROJ
**Description:** Project Scheme information
**Total Fields:** 18
**Key Fields:** MANDT, PROJNR

## Programs Using This Table
- `zisbi0013`
- `ziscs0005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROJNR` | CHAR | 24 | 🔑 | Project number |
| 3 | `ACTION` | CHAR | 1 |  | Action code |
| 4 | `DEPOT_CODE` | CHAR | 5 |  | Depot ID |
| 5 | `LTEXT` | CHAR | 40 |  | Long Text |
| 6 | `TXT04` | CHAR | 4 |  | User status |
| 7 | `ERDAT` | DATS | 8 |  | Created on |
| 8 | `PROJTP` | CHAR | 1 |  | Project type |
| 9 | `TGDAT` | DATS | 8 |  | Target on |
| 10 | `CHRG_TYPE` | CHAR | 1 |  | Main charge type |
| 11 | `CHRG_AMT` | CURR | 15 |  | Main charge amount |
| 12 | `NAME` | CHAR | 40 |  | Name 1 |
| 13 | `ADDR_1` | CHAR | 40 |  | Address |
| 14 | `ADDR_2` | CHAR | 40 |  | Address |
| 15 | `COND_REF` | CHAR | 40 |  | Condition letter reference number |
| 16 | `ENGINEER` | CHAR | 40 |  | Engineer in-charge name |
| 17 | `PAGER` | CHAR | 40 |  | Engineer pager number |
| 18 | `PSDATE` | DATS | 8 |  | Project Start Date |
