# ZIS_EEC_MTRDET
**Description:** Maintain the meter details
**Total Fields:** 20
**Key Fields:** MANDT, SERNO, START_DATE, END_DATE

## Programs Using This Table
- `ziscs0525`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNO` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `START_DATE` | DATS | 8 | 🔑 | Effective Start Date |
| 4 | `END_DATE` | DATS | 8 | 🔑 | Effective End Date |
| 5 | `SCENARIO` | CHAR | 2 |  | Scenarios for ZCS527 Report |
| 6 | `SCENARIO_TYPE` | CHAR | 20 |  | Scenario Type |
| 7 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 8 | `CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 9 | `RE_SOURCE` | CHAR | 2 |  | RE Source |
| 10 | `COMM_START_DATE` | DATS | 8 |  | Commissioning Start Date |
| 11 | `COMM_END_DATE` | DATS | 8 |  | Commissioning End Date |
| 12 | `RE_LOCATION` | CHAR | 100 |  | RE System Location Name |
| 13 | `EXI_GRID_NO` | CHAR | 40 |  | Existing grid connection agreement no |
| 14 | `NEW_GRID_NO` | CHAR | 40 |  | New grid connection agreement no |
| 15 | `NEW_CONN_DATE` | DATS | 8 |  | Field of type DATS |
| 16 | `CA_FOR_REPORTING` | CHAR | 12 |  | Contract Account Number |
| 17 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 20 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
