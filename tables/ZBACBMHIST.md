# ZBACBMHIST
**Description:** Runtime histroy of migration job
**Total Fields:** 23
**Key Fields:** S_NAME, S_DATE, S_TIME, S_ID, TVAL

## Programs Using This Table
- `zbacbe015`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `S_NAME` | CHAR | 12 | 🔑 | User name of person starting migration (migrator) |
| 2 | `S_DATE` | DATS | 8 | 🔑 | Starting date for migration |
| 3 | `S_TIME` | TIMS | 6 | 🔑 | Starting time of migration |
| 4 | `S_ID` | NUMC | 3 | 🔑 | Migration start ID |
| 5 | `TVAL` | NUMC | 10 | 🔑 | 10 digit number |
| 6 | `CNT_GOOD` | INT4 | 10 |  | Number of successfully created objects |
| 7 | `CNT_BAD` | INT4 | 10 |  | Number of unsuccessfully created objects |
| 8 | `DATUM` | DATS | 8 |  | Date |
| 9 | `UZEIT` | TIMS | 6 |  | Time |
| 10 | `RUNTIME` | INT4 | 10 |  | Runtime |
| 11 | `HOST` | CHAR | 20 |  | Host name for table TALIM |
| 12 | `AP_DEST` | CHAR | 32 |  | SAPOSCOL destination |
| 13 | `AP_USR` | INT4 | 10 |  | Data for tables to call "SAPOSCOL" |
| 14 | `AP_SYS` | INT4 | 10 |  | Data for tables to call "SAPOSCOL" |
| 15 | `AP_IDLE` | INT4 | 10 |  | Data for tables to call "SAPOSCOL" |
| 16 | `DB_DEST` | CHAR | 32 |  | SAPOSCOL destination |
| 17 | `DB_USR` | INT4 | 10 |  | Data for tables to call "SAPOSCOL" |
| 18 | `DB_SYS` | INT4 | 10 |  | Data for tables to call "SAPOSCOL" |
| 19 | `DB_IDLE` | INT4 | 10 |  | Data for tables to call "SAPOSCOL" |
| 20 | `MAXROLL` | INT4 | 10 |  | Statistics, counter field in raw statistical record |
| 21 | `MAXPAGE` | INT4 | 10 |  | Statistics, counter field in raw statistical record |
| 22 | `MEMSUM` | INT4 | 10 |  | Statistics, counter field in raw statistical record |
| 23 | `PRIVSUM` | INT4 | 10 |  | Statistics, counter field in raw statistical record |
