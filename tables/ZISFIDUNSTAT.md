# ZISFIDUNSTAT
**Description:** Dunning Statistics
**Total Fields:** 16
**Key Fields:** MANDT, P_KEY

## Programs Using This Table
- `zisbi0001`
- `zisbi0020`
- `zisbi0043`
- `zisbi0043n`
- `zisbi0083`
- `zisbi0270`
- `zisbi0270t`
- `ziscs0088`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `P_KEY` | CHAR | 12 | 🔑 | Character Field of Length 12 |
| 3 | `ZZBILLID` | CHAR | 2 |  | Bill ID |
| 4 | `BATCH_DATE` | DATS | 8 |  | Field of type DATS |
| 5 | `ISSUE_DATE` | DATS | 8 |  | Date of issue |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `AMOUNT` | CURR | 13 |  | Dunning Balance |
| 9 | `SPOOL` | CHAR | 4 |  | Spool: Output device |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `USER1` | CHAR | 12 |  | User Name |
| 12 | `TIME1` | TIMS | 6 |  | System Time |
| 13 | `LANGU` | LANG | 1 |  | Language Key |
| 14 | `DOCODE` | CHAR | 3 |  | District Office Code (obsolete) |
| 15 | `PBCODE` | CHAR | 12 |  | Postman Beat Code (obsolete) |
| 16 | `SENDCONTROL` | CHAR | 4 |  | Dispatch Control |
