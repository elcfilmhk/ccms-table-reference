# ZISCS_CI_CUST_IN
**Description:** C&I Customer data from Inbound Autogrid interface
**Total Fields:** 12
**Key Fields:** MANDT, DRCUSTNO, EVENTNAME, EVENT_DATE, START_TIME

## Programs Using This Table
- `ziscs_drevent_del`
- `zisdm0371`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `EVENTNAME` | CHAR | 50 | 🔑 | Event Name |
| 4 | `EVENT_DATE` | DATS | 8 | 🔑 | Participation Start date |
| 5 | `START_TIME` | TIMS | 6 | 🔑 | Participation start time |
| 6 | `GROUP_ID` | CHAR | 10 |  | Group ID |
| 7 | `END_TIME` | TIMS | 6 |  | Participation End Time |
| 8 | `BASELINE_USAGE_KWH` | DEC | 31 |  | Basleline Usage KWH |
| 9 | `ACTUAL_USAGE_KWH` | DEC | 31 |  | Actual Usage KWH |
| 10 | `ACTUAL_SHED_KWH` | DEC | 31 |  | Actual Shed KWH |
| 11 | `QUALIFIED_SHED_KWH` | DEC | 31 |  | Qualified Shed KWH |
| 12 | `INCENTIVE` | DEC | 16 |  | Incentive Payment |
