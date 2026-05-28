# ZISBICONSENTLTR
**Description:** Table for Consent Letter
**Total Fields:** 16
**Key Fields:** MANDT, BUDAT, VKONT

## Programs Using This Table
- `z_isu_sample_z1905============ft`
- `zisbi0166`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 5 | `CONSENT_DATE` | DATS | 8 |  | Consent Date |
| 6 | `EMAIL` | CHAR | 255 |  | Email Address |
| 7 | `SMS` | CHAR | 255 |  | SMS |
| 8 | `DISPATCH` | CHAR | 1 |  | Dispatch |
| 9 | `EBILL_SENDER` | CHAR | 100 |  | Sender Of Email |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 13 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 14 | `PRINT_TIME` | TIMS | 6 |  | System Time |
| 15 | `STATUS` | CHAR | 1 |  | Status |
| 16 | `ADRNB` | CHAR | 10 |  | Address number |
