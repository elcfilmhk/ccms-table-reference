# ZISBI_HISBILL
**Description:** Historical Bill Print
**Total Fields:** 6
**Key Fields:** MANDT, OPBEL, PRINTDATE, PRINTTIME

## Programs Using This Table
- `ziscs1138`
- `ziscs1139`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `PRINTDATE` | DATS | 8 | 🔑 | Date |
| 4 | `PRINTTIME` | TIMS | 6 | 🔑 | Time |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERGRD` | CHAR | 2 |  | Reason for creating print document |
