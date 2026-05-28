# ZISCSEVRFID
**Description:** RFID property
**Total Fields:** 15
**Key Fields:** MANDT, VENDOR, RFID

## Programs Using This Table
- `ziscs0502`
- `ziscs0504`
- `zisdm0219`
- `zisdm0226`
- `zisdm0227`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VENDOR` | CHAR | 4 | 🔑 | Vendor ID |
| 3 | `RFID` | CHAR | 20 | 🔑 | RFID |
| 4 | `STATUS` | CHAR | 1 |  | Status |
| 5 | `ADDAT` | DATS | 8 |  | Activation/Deactivation date |
| 6 | `ADTIM` | TIMS | 6 |  | Activation/Deactivation time |
| 7 | `DERSN` | CHAR | 1 |  | Deactivation reason |
| 8 | `CODAT` | DATS | 8 |  | Collection date |
| 9 | `COTIM` | TIMS | 6 |  | Collection time |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERTIM` | TIMS | 6 |  | Creation time |
| 12 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `AENZT` | TIMS | 6 |  | Changed At |
| 15 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
