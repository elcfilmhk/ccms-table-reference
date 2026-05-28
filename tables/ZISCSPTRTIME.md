# ZISCSPTRTIME
**Description:** PTR start/end time
**Total Fields:** 5
**Key Fields:** MANDT, DSMPROGID

## Programs Using This Table
- `ziscs0334`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DSMPROGID` | CHAR | 6 | 🔑 | DSM Program ID |
| 3 | `STIME` | TIMS | 6 |  | System Time |
| 4 | `ETIME` | TIMS | 6 |  | System Time |
| 5 | `PTRFUTDATE` | CHAR | 2 |  | PTR Future Days |
