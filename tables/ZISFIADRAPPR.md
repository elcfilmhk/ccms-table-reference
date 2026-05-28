# ZISFIADRAPPR
**Description:** ZDR10 - DR Payment Approval Limit Update
**Total Fields:** 7
**Key Fields:** MANDT, UNAME, BEGDA, ENDDA

## Programs Using This Table
- `zisdm0369_candi`
- `zisfi0249`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNAME` | CHAR | 12 | 🔑 | User Name |
| 3 | `BEGDA` | DATS | 8 | 🔑 | Start Date |
| 4 | `ENDDA` | DATS | 8 | 🔑 | End Date |
| 5 | `MAX_AMT` | CURR | 13 |  | Amount To |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
