# ZIS_EEC_FITAPHIS
**Description:** FiT Application Approval Data
**Total Fields:** 16
**Key Fields:** MANDT, RE_APP_NO, RE_SYS_LOC, RE_SOURCE, LOGIKNR, BEGDA, PAST

## Programs Using This Table
- `ziscs0518`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `RE_SYS_LOC` | CHAR | 10 | 🔑 | RE System Location |
| 4 | `RE_SOURCE` | CHAR | 2 | 🔑 | RE Source |
| 5 | `LOGIKNR` | NUMC | 18 | 🔑 | Logical device number |
| 6 | `BEGDA` | DATS | 8 | 🔑 | Start Date |
| 7 | `PAST` | CHAR | 1 | 🔑 | General Flag |
| 8 | `ENDDA` | DATS | 8 |  | End Date |
| 9 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 10 | `FIT_METR_FLAG` | CHAR | 1 |  | New FiT Meter Flag |
| 11 | `FIT_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 12 | `FIT_RATE` | DEC | 4 |  | FiT Rate |
| 13 | `TOT_DAYS` | DEC | 6 |  | Service Credit in Days |
| 14 | `AMOUNT` | CURR | 13 |  | Amount |
| 15 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 16 | `RE_PARENT_APP` | CHAR | 12 |  | Notification No |
