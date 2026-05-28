# ZISCSEVRFIDCHRTN
**Description:** RFID activation/deactivation for interface file generation
**Total Fields:** 13
**Key Fields:** MANDT, VENDOR, RFID, ERDAT, ERTIM

## Programs Using This Table
- `ziscs0502`
- `ziscs0503`
- `ziscs0504`
- `zisdm0286`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VENDOR` | CHAR | 4 | 🔑 | Vendor ID |
| 3 | `RFID` | CHAR | 20 | 🔑 | RFID |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERTIM` | TIMS | 6 | 🔑 | Creation time |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENZT` | TIMS | 6 |  | Changed At |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `ACTION` | CHAR | 1 |  | Action |
| 11 | `STATUS` | CHAR | 1 |  | Status |
| 12 | `CNRESN` | CHAR | 1 |  | Cancel reason |
| 13 | `TRNUM` | CHAR | 12 |  | File number |
