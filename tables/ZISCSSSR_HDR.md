# ZISCSSSR_HDR
**Description:** SSR Contract Accounts Assignment
**Total Fields:** 13
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zcl_ssr_program`
- `zisdm0364`
- `zisdm0366`
- `zrca_ssr_assign_upload`
- `zrca_ssr_cust_extract`
- `zrca_ssr_program_upload`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 8 | `AUTOGRID` | CHAR | 1 |  | AutoGrid |
| 9 | `EMAIL_NOTIFY` | CHAR | 1 |  | Email Notification Preference Flag |
| 10 | `SMS_NOTIFY` | CHAR | 1 |  | SMS Notification preference Flag |
| 11 | `EMAIL_BYPASS_MC` | CHAR | 1 |  | Email ByPass MC Flag |
| 12 | `SMS_BYPASS_MC` | CHAR | 1 |  | SMS Bypass MC Flag |
| 13 | `NOTIFY_AEDAT` | DATS | 8 |  | SSR Notif Last Change Date |
