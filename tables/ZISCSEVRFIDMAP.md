# ZISCSEVRFIDMAP
**Description:** RFID CA mapping
**Total Fields:** 18
**Key Fields:** MANDT, VKONT, VENDOR, RFID

## Programs Using This Table
- `zisbi0136`
- `ziscs0502`
- `ziscs0504`
- `ziscs0505`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `VENDOR` | CHAR | 4 | 🔑 | Vendor ID |
| 4 | `RFID` | CHAR | 20 | 🔑 | RFID |
| 5 | `BITDAT` | DATS | 8 |  | Valid to date |
| 6 | `BITTIM` | TIMS | 6 |  | Valid to time |
| 7 | `BIFDAT` | DATS | 8 |  | Valid from date |
| 8 | `BIFTIM` | TIMS | 6 |  | Valid from time |
| 9 | `RATCA` | CHAR | 12 |  | Re-assigned to CA |
| 10 | `RADAT` | DATS | 8 |  | Re-assigned from date |
| 11 | `RACRT` | DATS | 8 |  | Re-assigned creation date |
| 12 | `RATIM` | TIMS | 6 |  | Re-assigned creation time |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `ERTIM` | TIMS | 6 |  | Creation time |
| 15 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 16 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 17 | `AENZT` | TIMS | 6 |  | Changed At |
| 18 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
