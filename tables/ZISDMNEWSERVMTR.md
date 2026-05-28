# ZISDMNEWSERVMTR
**Description:** New Service Meter reported
**Total Fields:** 18
**Key Fields:** MANDT, REPORT_DATE, REPORT_TYPE, PREMISE, DEVICE_NUMBER, SCHED_MR_DATE

## Programs Using This Table
- `zisdm0129`
- `zisdm0130`
- `zisdm0137`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `REPORT_TYPE` | CHAR | 1 | 🔑 | Report Type |
| 4 | `PREMISE` | CHAR | 10 | 🔑 | Premise |
| 5 | `DEVICE_NUMBER` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `SCHED_MR_DATE` | DATS | 8 | 🔑 | Date |
| 7 | `ACTUAL_MR_DATE` | DATS | 8 |  | Date |
| 8 | `READING` | CHAR | 10 |  | Reading |
| 9 | `NEXT_MTER_NO` | CHAR | 18 |  | Serial Number |
| 10 | `METER_READER_ID` | CHAR | 8 |  | User ID |
| 11 | `PCID` | CHAR | 6 |  | Additional Identification Characteristic |
| 12 | `NEXT_PREMISE` | CHAR | 10 |  | Premise |
| 13 | `DEV_INSTALL_DATE` | DATS | 8 |  | Installation date |
| 14 | `REGIOGROUP` | CHAR | 8 |  | Regional structure grouping |
| 15 | `CONSUMPTION` | DEC | 13 |  | Consumption - Device Level |
| 16 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 17 | `DEPOT_ID` | CHAR | 5 |  | Depot ID |
| 18 | `ANLAGE` | CHAR | 10 |  | Installation |
