# ZISDMCONSECESTMR
**Description:** Consective Meter data
**Total Fields:** 30
**Key Fields:** MANDT, REPORT_MONTH, SERNR

## Programs Using This Table
- `zisdm0271`
- `zisdm0272`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT_MONTH` | CHAR | 7 | 🔑 | Reporting Month of the report in CCYY-MM format |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ANLAGE` | CHAR | 10 |  | Installation |
| 5 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 6 | `MR_GROUP` | CHAR | 2 |  | MR Group |
| 7 | `OC` | CHAR | 3 |  | Operation Centre |
| 8 | `READING_METHOD` | CHAR | 4 |  | Meter Reading Method |
| 9 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 10 | `NO_OF_BILL_CYCLE` | DEC | 3 |  | Number of Bill Cycle |
| 11 | `NO_OF_CYCLE` | CHAR | 10 |  | Number of periodic reading cycle estimated |
| 12 | `NO_OF_MONTH` | CHAR | 10 |  | Number of Months estimated |
| 13 | `LAST_ACTUAL_RDG` | DATS | 8 |  | Last actual meter reading date |
| 14 | `LAST_ACTUAL_READ` | DEC | 31 |  | Last Actual reading |
| 15 | `ACTIVE` | CHAR | 1 |  | Indicator for active contract exists for the installation |
| 16 | `INACTIVE` | CHAR | 1 |  | Indicator for no active contract exists for the installation |
| 17 | `CONNECTED` | CHAR | 1 |  | Indicator for the device is connected |
| 18 | `DISCONNECTED` | CHAR | 1 |  | Indicator for the device is disonccected |
| 19 | `MAIN` | CHAR | 1 |  | Indicator for the meter is a main meter |
| 20 | `CHECK_IND` | CHAR | 1 |  | Indicator for the meter is a check meter |
| 21 | `ACTOR` | CHAR | 14 |  | Concatenated Identification (Type and ID) of Org.Objects |
| 22 | `SUPPLY_ADDRESS` | CHAR | 150 |  | Supply Address of the installation |
| 23 | `POSTAL_ADDRESS` | CHAR | 150 |  | Postal Address of the installation |
| 24 | `STORTZUS` | CHAR | 30 |  | Addition to device location |
| 25 | `ACTUAL_RDG_DATE` | DATS | 8 |  | Actual meter reading date found after report |
| 26 | `ACTUAL_RDG_AR` | DEC | 31 |  | Actual Reading after report |
| 27 | `ACTUAL_RR_AR` | CHAR | 2 |  | Actual Meter Reading Reason after report |
| 28 | `ACTUAL_MT_AR` | CHAR | 2 |  | Actual Meter Reading Type after report |
| 29 | `ACTUAL_MRID_AR` | CHAR | 10 |  | Staff ID |
| 30 | `LAST_ESTIMATE_READ` | DEC | 31 |  | Last estimated reading |
