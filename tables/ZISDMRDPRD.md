# ZISDMRDPRD
**Description:** Meter Reading Type period table
**Total Fields:** 7
**Key Fields:** MANDT, ZMRTYPE, AUART, ILART

## Programs Using This Table
- `zisdm0025`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZMRTYPE` | CHAR | 1 | 🔑 | The Meter Reading Type |
| 3 | `AUART` | CHAR | 4 | 🔑 | Order Type |
| 4 | `ILART` | CHAR | 3 | 🔑 | Maintenance activity type |
| 5 | `ZDESCRIPTION` | CHAR | 40 |  | Description for the meter reading request |
| 6 | `ZSTRTDATETYPE` | CHAR | 1 |  | The start date of the reading period |
| 7 | `ZRDGPERD` | NUMC | 3 |  | Number of days for period length |
