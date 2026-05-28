# ZISBIMCLOG
**Description:** Print documents in marketing campaign list
**Total Fields:** 13
**Key Fields:** MANDT, DATUM1, OPBEL, TIME1, USER1, VKONT

## Programs Using This Table
- `zisbi0150`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM1` | DATS | 8 | 🔑 | Date |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `TIME1` | TIMS | 6 | 🔑 | System Time |
| 5 | `USER1` | CHAR | 12 | 🔑 | User Name |
| 6 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `INSERT_NO` | NUMC | 10 |  | Insert Number |
| 9 | `MESSAGE_NO` | NUMC | 10 |  | Message number |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `AREA` | CHAR | 8 |  | Regional structure area |
| 12 | `GROUP1` | CHAR | 8 |  | Regional structure grouping |
| 13 | `BILL_TYPE` | CHAR | 2 |  | Bill ID |
