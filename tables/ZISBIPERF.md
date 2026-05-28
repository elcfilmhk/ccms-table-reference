# ZISBIPERF
**Description:** Performance results from bill printout
**Total Fields:** 13
**Key Fields:** MANDT, PKEY

## Programs Using This Table
- `zisbiperf`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PKEY` | CHAR | 20 | 🔑 | From number |
| 3 | `DESCRIPTION` | CHAR | 30 |  | 30 Characters |
| 4 | `WEIGHT` | NUMC | 10 |  | Numeric Character Field, Length 10 |
| 5 | `TIME` | INT4 | 10 |  | Natural number |
| 6 | `USERNAME` | CHAR | 12 |  | User Name |
| 7 | `CURR_DATE` | DATS | 8 |  | System Date |
| 8 | `CURR_TIME` | TIMS | 6 |  | System Time |
| 9 | `ZZBILLID` | CHAR | 2 |  | Bill ID |
| 10 | `OPBEL` | CHAR | 12 |  | Number of print document |
| 11 | `OTHER_INFO` | CHAR | 100 |  | Character 100 |
| 12 | `BATCH` | CHAR | 20 |  | From number |
| 13 | `FORMKEY` | CHAR | 30 |  | Application form |
