# ZIS_ALERT_RUNHIS
**Description:** Run history for Projected Consumption Alert
**Total Fields:** 14
**Key Fields:** MANDT, ALERT_TYPE, RUNDATE, PARAM1, PARAM2, PARAM3, COUNTER

## Programs Using This Table
- `ziscs0734`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ALERT_TYPE` | CHAR | 2 | 🔑 | Alert Type |
| 3 | `RUNDATE` | DATS | 8 | 🔑 | Last Run Date |
| 4 | `PARAM1` | CHAR | 2 | 🔑 | Portion |
| 5 | `PARAM2` | CHAR | 2 | 🔑 | Frequency Days (UN) |
| 6 | `PARAM3` | CHAR | 2 | 🔑 | Mod Value Current Run (UN) |
| 7 | `COUNTER` | NUMC | 5 | 🔑 | Counter |
| 8 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 9 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 10 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `ERZET` | TIMS | 6 |  | Entry time |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 14 | `AEZET` | TIMS | 6 |  | Time last change was made |
