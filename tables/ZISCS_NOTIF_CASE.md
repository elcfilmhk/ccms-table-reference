# ZISCS_NOTIF_CASE
**Description:** Notify cases
**Total Fields:** 13
**Key Fields:** MANDT, CASE_ID

## Programs Using This Table
- `ziscs0372`
- `ziscs0460`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CASE_ID` | INT4 | 10 | 🔑 | Notify Case ID |
| 3 | `CASE_CREATE_DT` | CHAR | 14 |  | Notify Case Creation Datetime |
| 4 | `SERVICE_TYPE` | CHAR | 1 |  | Type of eService |
| 5 | `CASE_TYPE` | CHAR | 50 |  | Case Type of "Notify Case" Object |
| 6 | `SOURCE` | CHAR | 10 |  | Source of a Notify Case |
| 7 | `SOURCE_REF_NO` | CHAR | 80 |  | Reference number to refer back to source system |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `PREMISE` | CHAR | 10 |  | Premise |
| 10 | `METER_NO` | CHAR | 18 |  | Serial Number |
| 11 | `CASE_CLOSED_DT` | CHAR | 14 |  | Notify Case Closed Datetime (Blank = Case still Open) |
| 12 | `LAST_POLL_STATUS` | CHAR | 50 |  | Status last polled from Source System |
| 13 | `LAST_STATUS_DT` | CHAR | 14 |  | Status Change Datetime |
