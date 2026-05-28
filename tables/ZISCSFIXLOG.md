# ZISCSFIXLOG
**Description:** Fixed Date Billing change log
**Total Fields:** 7
**Key Fields:** MANDT, VERTRAG, CDATE, CTIME

## Programs Using This Table
- `ziscs0158`
- `ziscs0160`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 3 | `CDATE` | DATS | 8 | 🔑 | Creation Date |
| 4 | `CTIME` | TIMS | 6 | 🔑 | Created at |
| 5 | `CUSER` | CHAR | 12 |  | Created By |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `ACTION` | CHAR | 1 |  | Action |
