# ZISBISMSLTRSENT
**Description:** Custom Table for SMS Registration Letters sent daily
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, GPART, ERDAT, ERZEIT

## Programs Using This Table
- `zisbi0137`
- `zisbi0141`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `PHONENO` | CHAR | 20 |  | SMS billing telephone number |
| 8 | `SENDDATE` | DATS | 8 |  | Send Date |
