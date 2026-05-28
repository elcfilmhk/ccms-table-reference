# ZISDMPMTRSWITCH
**Description:** Storing pre-meter switch data from the daily MR upload
**Total Fields:** 13
**Key Fields:** MANDT, DATUM, ANLAGE, SERNR, ABLESGR

## Programs Using This Table
- `zisdm0050`
- `zisdm0192`
- `zisdm0216`
- `zisdm0229`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | Batch run date |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 6 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 7 | `MREADER` | CHAR | 8 |  | Meter reader |
| 8 | `ADATTATS` | DATS | 8 |  | Actual meter reading date |
| 9 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 10 | `CHANGECODE1` | CHAR | 2 |  | Changed Note Indicator |
| 11 | `CHANGECODE2` | CHAR | 2 |  | Changed Note Indicator |
| 12 | `CHANGECODE3` | CHAR | 2 |  | Changed Note Indicator |
| 13 | `ZZJOBSTAT` | CHAR | 2 |  | Job Status of meter reading action |
