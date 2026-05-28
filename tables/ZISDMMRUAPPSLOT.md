# ZISDMMRUAPPSLOT
**Description:** MRU appointment slot
**Total Fields:** 21
**Key Fields:** MANDT, ID

## Programs Using This Table
- `zisdm0243`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ID` | NUMC | 10 | 🔑 | ID for appointment slot |
| 3 | `MRUGROUPZONE` | CHAR | 3 |  | The MRU Group and Zone |
| 4 | `MRUCODE` | CHAR | 1 |  | The MRU Code |
| 5 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 6 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 7 | `DAYOFWEEKMON` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 8 | `DAYOFWEEKTUE` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 9 | `DAYOFWEEKWED` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 10 | `DAYOFWEEKTHU` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 11 | `DAYOFWEEKFRI` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 12 | `DAYOFMONTH1` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 13 | `DAYOFMONTH2` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 14 | `DAYOFMONTH3` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 15 | `DAYOFMONTH4` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 16 | `DAYOFMONTH5` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 17 | `REMARK` | CHAR | 50 |  | Remark |
| 18 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 19 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 20 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 21 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
