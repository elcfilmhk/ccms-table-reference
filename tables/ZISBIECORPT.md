# ZISBIECORPT
**Description:** ECO alert log table
**Total Fields:** 46
**Key Fields:** MANDT, OBPEL

## Programs Using This Table
- `zisbi0161`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBPEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `CUR_AB` | DATS | 8 |  | Current Period From Date |
| 7 | `CUR_BIS` | DATS | 8 |  | Current Period To Date |
| 8 | `CUR_DAYS` | NUMC | 6 |  | Current No. of consumption days |
| 9 | `CUR_BILLID` | CHAR | 2 |  | Bill ID |
| 10 | `PRE_DAYS` | NUMC | 6 |  | Previous No. Of Consumption Days |
| 11 | `ACTPERIOD` | CHAR | 40 |  | Category of a period for previous billing |
| 12 | `COMP_PERIOD` | NUMC | 2 |  | No. Of Consumption Period |
| 13 | `COMP_DATE_01` | DATS | 8 |  | Consumption Date 01 |
| 14 | `TOTAL_COMP_01` | DEC | 16 |  | Consumption 01 |
| 15 | `COMP_DATE_02` | DATS | 8 |  | Consumption Date 02 |
| 16 | `TOTAL_COMP_02` | DEC | 16 |  | Consumption 02 |
| 17 | `COMP_DATE_03` | DATS | 8 |  | Consumption Date 03 |
| 18 | `TOTAL_COMP_03` | DEC | 16 |  | Consumption 03 |
| 19 | `COMP_DATE_04` | DATS | 8 |  | Consumption Date 04 |
| 20 | `TOTAL_COMP_04` | DEC | 16 |  | Consumption 04 |
| 21 | `COMP_DATE_05` | DATS | 8 |  | Consumption Date 05 |
| 22 | `TOTAL_COMP_05` | DEC | 16 |  | Consumption 05 |
| 23 | `COMP_DATE_06` | DATS | 8 |  | Consumption Date 06 |
| 24 | `TOTAL_COMP_06` | DEC | 16 |  | Consumption 06 |
| 25 | `COMP_DATE_07` | DATS | 8 |  | Consumption Date 07 |
| 26 | `TOTAL_COMP_07` | DEC | 16 |  | Consumption 07 |
| 27 | `COMP_DATE_08` | DATS | 8 |  | Consumption Date 08 |
| 28 | `TOTAL_COMP_08` | DEC | 16 |  | Consumption 08 |
| 29 | `COMP_DATE_09` | DATS | 8 |  | Consumption Date 09 |
| 30 | `TOTAL_COMP_09` | DEC | 16 |  | Consumption 09 |
| 31 | `COMP_DATE_10` | DATS | 8 |  | Consumption Date 10 |
| 32 | `TOTAL_COMP_10` | DEC | 16 |  | Consumption 10 |
| 33 | `COMP_DATE_11` | DATS | 8 |  | Consumption Date 11 |
| 34 | `TOTAL_COMP_11` | DEC | 16 |  | Consumption 11 |
| 35 | `COMP_DATE_12` | DATS | 8 |  | Consumption Date 12 |
| 36 | `TOTAL_COMP_12` | DEC | 16 |  | Consumption 12 |
| 37 | `COMP_DATE_13` | DATS | 8 |  | Consumption Date 13 |
| 38 | `TOTAL_COMP_13` | DEC | 16 |  | Consumption 13 |
| 39 | `COMP_DATE_14` | DATS | 8 |  | Consumption Date 14 |
| 40 | `TOTAL_COMP_14` | DEC | 16 |  | Consumption 14 |
| 41 | `PREV_AB` | DATS | 8 |  | Last Year Same Period From Date |
| 42 | `PREV_BIS` | DATS | 8 |  | Last Year Same Period To Date |
| 43 | `LAST_YR_COMP` | DEC | 16 |  | Last Year Same Period Consumption |
| 44 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 45 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 46 | `CREATION_TIME` | TIMS | 6 |  | Creation Time |
