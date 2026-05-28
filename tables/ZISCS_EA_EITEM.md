# ZISCS_EA_EITEM
**Description:** EA EMO/ESO/Smart IT summary
**Total Fields:** 15
**Key Fields:** MANDT, EA_APP_NO, EMO_CAT, EMO_SUM_ITEM, AFFNR

## Programs Using This Table
- `ziscs0526`
- `ziscs0723`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EA_APP_NO` | CHAR | 12 | 🔑 | Energy Audit Application |
| 3 | `EMO_CAT` | CHAR | 2 | 🔑 | EMO Summary Category |
| 4 | `EMO_SUM_ITEM` | CHAR | 3 | 🔑 | EMO Summary Item |
| 5 | `AFFNR` | NUMC | 5 | 🔑 | Identification Number |
| 6 | `EMO_ITM_STATUS` | CHAR | 2 |  | EMO Item Status |
| 7 | `EXP_SAVING` | DEC | 25 |  | Expected Saving(KWh) |
| 8 | `PRO_COST` | CURR | 13 |  | Project Cost |
| 9 | `PAYBACK` | CHAR | 10 |  | Payback |
| 10 | `COMM_DAT` | DATS | 8 |  | Commissioning Date |
| 11 | `ACT_SAVING` | DEC | 25 |  | Actual Energy Saving (GWh) |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 15 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
