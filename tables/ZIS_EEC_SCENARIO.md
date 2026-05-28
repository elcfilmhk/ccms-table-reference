# ZIS_EEC_SCENARIO
**Description:** Report Scenarios for RE Generation & Send Out report -ZCS527
**Total Fields:** 9
**Key Fields:** MANDT, SCENARIO

## Programs Using This Table
- `ziscs0525`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCENARIO` | CHAR | 2 | 🔑 | Scenarios for ZCS527 Report |
| 3 | `SCENARIO_TYPE` | CHAR | 20 |  | Scenario Type |
| 4 | `GOVT_IND` | CHAR | 1 |  | Government Indicator |
| 5 | `SCENARIO_NAME` | CHAR | 100 |  | Scenario Name |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
