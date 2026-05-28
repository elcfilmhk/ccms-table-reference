# ZISBI_PTR_DATA
**Description:** AMI Analytics Data
**Total Fields:** 57
**Key Fields:** MANDT, PTR_DATE_KEY, VKONTO

## Programs Using This Table
- `zisbi0172_ptr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PTR_DATE_KEY` | DATS | 8 | 🔑 | PTR Event Date |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Account Number |
| 4 | `TARIFTYP` | CHAR | 10 |  | Rate Category |
| 5 | `STR_ERG2` | CHAR | 40 |  | Str. Suppl. 1 |
| 6 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 7 | `STREET` | CHAR | 60 |  | Street |
| 8 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 9 | `CITY2` | CHAR | 40 |  | District |
| 10 | `SEGMENT` | CHAR | 20 |  | Segment Group |
| 11 | `KTOTX` | CHAR | 40 |  | Trade Name |
| 12 | `NOTE` | CHAR | 2 |  | AMI Customer group |
| 13 | `KONDIGR` | CHAR | 10 |  | Fact Group |
| 14 | `ERR_MSG` | CHAR | 40 |  | Error Message |
| 15 | `TOP1_DATE` | DATS | 8 |  | Top1 Date |
| 16 | `TOP1_USAGE1` | CHAR | 30 |  | 18:00 |
| 17 | `TOP1_USAGE2` | CHAR | 30 |  | 18:30 |
| 18 | `TOP1_USAGE3` | CHAR | 30 |  | 19:00 |
| 19 | `TOP1_USAGE4` | CHAR | 30 |  | 19:30 |
| 20 | `TOP1_USAGE5` | CHAR | 30 |  | 20:00 |
| 21 | `TOP1_USAGE6` | CHAR | 30 |  | 20:30 |
| 22 | `TOP1_USAGE7` | CHAR | 30 |  | 21:00 |
| 23 | `TOP1_USAGE8` | CHAR | 30 |  | 21:30 |
| 24 | `TOP2_DATE` | DATS | 8 |  | Top2 Date |
| 25 | `TOP2_USAGE1` | CHAR | 30 |  | 18:00 |
| 26 | `TOP2_USAGE2` | CHAR | 30 |  | 18:30 |
| 27 | `TOP2_USAGE3` | CHAR | 30 |  | 19:00 |
| 28 | `TOP2_USAGE4` | CHAR | 30 |  | 19:30 |
| 29 | `TOP2_USAGE5` | CHAR | 30 |  | 20:00 |
| 30 | `TOP2_USAGE6` | CHAR | 30 |  | 20:30 |
| 31 | `TOP2_USAGE7` | CHAR | 30 |  | 21:00 |
| 32 | `TOP2_USAGE8` | CHAR | 30 |  | 21:30 |
| 33 | `TOP3_DATE` | DATS | 8 |  | Top3 Date |
| 34 | `TOP3_USAGE1` | CHAR | 30 |  | 18:00 |
| 35 | `TOP3_USAGE2` | CHAR | 30 |  | 18:30 |
| 36 | `TOP3_USAGE3` | CHAR | 30 |  | 19:00 |
| 37 | `TOP3_USAGE4` | CHAR | 30 |  | 19:30 |
| 38 | `TOP3_USAGE5` | CHAR | 30 |  | 20:00 |
| 39 | `TOP3_USAGE6` | CHAR | 30 |  | 20:30 |
| 40 | `TOP3_USAGE7` | CHAR | 30 |  | 21:00 |
| 41 | `TOP3_USAGE8` | CHAR | 30 |  | 21:30 |
| 42 | `PTR_DATE` | DATS | 8 |  | PTR Event Date |
| 43 | `PRT_USAGE1` | CHAR | 30 |  | 18:00 |
| 44 | `PRT_USAGE2` | CHAR | 30 |  | 18:30 |
| 45 | `PRT_USAGE3` | CHAR | 30 |  | 19:00 |
| 46 | `PRT_USAGE4` | CHAR | 30 |  | 19:30 |
| 47 | `PRT_USAGE5` | CHAR | 30 |  | 20:00 |
| 48 | `PRT_USAGE6` | CHAR | 30 |  | 20:30 |
| 49 | `PRT_USAGE7` | CHAR | 30 |  | 21:00 |
| 50 | `PRT_USAGE8` | CHAR | 30 |  | 21:30 |
| 51 | `BASELINE` | DEC | 21 |  | Baseline (kwh) |
| 52 | `ACTUAL` | DEC | 21 |  | Actual (kwh) |
| 53 | `CUT_LOAD` | DEC | 21 |  | Cut-load  (kwh) |
| 54 | `PTR_REB` | DEC | 17 |  | PTR Rebate Amount |
| 55 | `CREATE_DATE` | DATS | 8 |  | Created on |
| 56 | `CREATE_TIME` | TIMS | 6 |  | Time of creation |
| 57 | `CREATE_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
