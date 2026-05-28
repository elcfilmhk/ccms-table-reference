# ZISBI_FITREBATE
**Description:** FiT Rebate for Each device (To be used in Bill printing)
**Total Fields:** 19
**Key Fields:** MANDT, BELNR, VKONT, GERAET, AB_FITRATE, BIS_FITRATE

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`
- `zisbi0239`
- `ziscs0517`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `GERAET` | CHAR | 18 | 🔑 | Device |
| 5 | `AB_FITRATE` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 6 | `BIS_FITRATE` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 7 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 8 | `NUM_DAYS` | INT2 | 5 |  | Number of Days |
| 9 | `FIT_GENERATION` | DEC | 31 |  | Profile value at application level |
| 10 | `FIT_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 11 | `FIT_RATE` | DEC | 4 |  | FiT Rate |
| 12 | `FIT_REBATE_AMT` | CURR | 13 |  | FiT Rebate Amount for Device |
| 13 | `RE_SYS_LOC` | CHAR | 10 |  | RE System Location |
| 14 | `RE_SYS_NAME` | CHAR | 100 |  | RE System Location Name |
| 15 | `RE_SYS_NAME_CH` | CHAR | 100 |  | Description |
| 16 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 17 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 18 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 19 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
