# ZISDMCONNAPPSLOT
**Description:** Connection object appointment slot
**Total Fields:** 20
**Key Fields:** MANDT, ID

## Programs Using This Table
- `zisdm0242`
- `zisdm0243`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ID` | NUMC | 10 | 🔑 | ID for appointment slot |
| 3 | `HAUS` | CHAR | 30 |  | Functional Location |
| 4 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 5 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 6 | `DAYOFWEEKMON` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 7 | `DAYOFWEEKTUE` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 8 | `DAYOFWEEKWED` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 9 | `DAYOFWEEKTHU` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 10 | `DAYOFWEEKFRI` | CHAR | 1 |  | Day of Week 'X' - Available for appointment |
| 11 | `DAYOFMONTH1` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 12 | `DAYOFMONTH2` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 13 | `DAYOFMONTH3` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 14 | `DAYOFMONTH4` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 15 | `DAYOFMONTH5` | NUMC | 2 |  | Day of month available for appointment Must >=1 and <= 31 |
| 16 | `REMARK` | CHAR | 50 |  | Remark |
| 17 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 20 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
