# ZIS_EEC_REMTRHIS
**Description:** FiT Device Location to Meter Info - History
**Total Fields:** 28
**Key Fields:** MANDT, RE_APP_NO, RE_SYS_LOC, RE_SOURCE, LOGIKNR, COMM_END_DATE

## Programs Using This Table
- `zisdm0022`
- `zisdm0022_bulk`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `RE_SYS_LOC` | CHAR | 10 | 🔑 | RE System Location |
| 4 | `RE_SOURCE` | CHAR | 2 | 🔑 | RE Source |
| 5 | `LOGIKNR` | NUMC | 18 | 🔑 | Logical device number |
| 6 | `COMM_END_DATE` | DATS | 8 | 🔑 | Commissioning End Date |
| 7 | `COMM_START_DATE` | DATS | 8 |  | Commissioning Start Date |
| 8 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 9 | `FIT_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 10 | `FIT_RATE` | DEC | 4 |  | FiT Rate |
| 11 | `FIT_RATE_TO_BE` | DEC | 4 |  | FiT Rate |
| 12 | `MET_LOC_DESC` | CHAR | 50 |  | Meter Location Description |
| 13 | `MET_DOC_LINK` | CHAR | 250 |  | Meter Document link |
| 14 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 15 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 16 | `ZZMETERSIZE` | CHAR | 18 |  | Size/dimension |
| 17 | `ZZMETERROLE` | CHAR | 30 |  | Meter Role |
| 18 | `ZZDEVLOC` | CHAR | 30 |  | Device Location |
| 19 | `RE_SOURCE_FIT_RATE` | CHAR | 2 |  | RE Source |
| 20 | `RE_SYS_NAM_CH` | CHAR | 100 |  | Description |
| 21 | `OLD_METER` | CHAR | 18 |  | Device |
| 22 | `OLD_METER_1` | CHAR | 18 |  | Device |
| 23 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 24 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 25 | `ERZET` | TIMS | 6 |  | Entry time |
| 26 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 27 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 28 | `AEZET` | TIMS | 6 |  | Time last change was made |
