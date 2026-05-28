# ZISBIGRNINVITE
**Description:** Table of Green Bill Invitation Letter when Trial Scheme end
**Total Fields:** 9
**Key Fields:** MANDT, ERDAT, VKONT

## Programs Using This Table
- `zisbi0155`
- `zisbi0156`
- `zisfi0266`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 5 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 6 | `TRIAL_ENDDATE` | DATS | 8 |  | End date for Green Bill Trial Scheme |
| 7 | `TRIAL_ENDDATE_P1` | DATS | 8 |  | End date for Green Bill Trial Scheme +1 |
| 8 | `PRINT_DATE` | DATS | 8 |  | Print Date |
| 9 | `PRINT_TIME` | TIMS | 6 |  | Print Time |
