# ZIS_EEC_FITMETER
**Description:** RE Application V Location Mapping
**Total Fields:** 21
**Key Fields:** MANDT, RE_APP_NO, RE_SYS_LOC, RE_SOURCE

## Programs Using This Table
- `ziscs0507`
- `ziscs0511`
- `ziscs0514`
- `ziscs0515`
- `ziscs0518`
- `ziscs1122`
- `zisdm0022_bulk`
- `zpc_rank_patch`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `RE_SYS_LOC` | CHAR | 10 | 🔑 | RE System Location |
| 4 | `RE_SOURCE` | CHAR | 2 | 🔑 | RE Source |
| 5 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 6 | `RE_ATYPE` | CHAR | 2 |  | Application Type |
| 7 | `PROV_FIT_TOT_CAP` | QUAN | 9 |  | Total RE/FiT Capacity at Location(kW) |
| 8 | `PROV_APP_FIT_CAP` | QUAN | 9 |  | Application RE/FiT Capacity at Location(kW) |
| 9 | `FIT_METR_FLAG` | CHAR | 1 |  | New FiT Meter Flag |
| 10 | `PROV_FIT_RATE` | DEC | 4 |  | FiT Rate |
| 11 | `ELEC_OUTPUT` | CHAR | 1 |  | Electricity Output(in phase) |
| 12 | `EDMS_LINK` | CHAR | 250 |  | EDMS Link (Operation Procedure) |
| 13 | `DEL_FLAG` | CHAR | 1 |  | Deletion Flag |
| 14 | `RE_SOURCE_FIT_RATE` | CHAR | 2 |  | RE Source |
| 15 | `RE_SYS_NAM_CH` | CHAR | 100 |  | Description |
| 16 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 17 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 18 | `ERZET` | TIMS | 6 |  | Entry time |
| 19 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 20 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 21 | `AEZET` | TIMS | 6 |  | Time last change was made |
