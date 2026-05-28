# ZIS_EEC_INSTDET
**Description:** Additional Installation of RE systems for Surplus Reporting
**Total Fields:** 12
**Key Fields:** MANDT, ANLAGE, START_DATE, END_DATE

## Programs Using This Table
- `ziscs0525`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `START_DATE` | DATS | 8 | 🔑 | Effective Start Date |
| 4 | `END_DATE` | DATS | 8 | 🔑 | Effective End Date |
| 5 | `SCENARIO` | CHAR | 2 |  | Scenarios for ZCS527 Report |
| 6 | `SCENARIO_TYPE` | CHAR | 20 |  | Scenario Type |
| 7 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 8 | `CA_FOR_REPORTING` | CHAR | 12 |  | Contract Account Number |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 12 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
