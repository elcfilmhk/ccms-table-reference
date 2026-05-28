# ZISFIMCJB
**Description:** MCRS Realtime Job table
**Total Fields:** 12
**Key Fields:** MANDT, DATEID, LAUFI

## Programs Using This Table
- `zisfimcrf`
- `zisfimcvw`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATEID` | DATS | 8 | 🔑 | Date ID |
| 3 | `LAUFI` | CHAR | 5 | 🔑 | Identification for the payment run |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `AMOUNT` | CHAR | 10 |  | MCRS Refund Amount |
| 6 | `.INCLUDE` | &nbsp; | 0 |  | Payment program - data for payment - MCRS Transaction Detail |
| 7 | `ZZTXID` | NUMC | 5 |  | MCRS Transaction ID |
| 8 | `ZZLOCATIONID` | NUMC | 2 |  | MCRS Location ID |
| 9 | `ZZMID` | CHAR | 1 |  | Machine ID |
| 10 | `STARTTIME` | TIMS | 6 |  | System Time |
| 11 | `ENDTIME` | TIMS | 6 |  | System Time |
| 12 | `STATUS` | CHAR | 1 |  | MCRS Status - Waiting, Running, Complete |
