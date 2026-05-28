# ZISCSOTPDETAILSH
**Description:** History table for ZISCSOTPDETAILS
**Total Fields:** 16
**Key Fields:** MANDT, TIMESTAMP, UNIQUE_ID, CONTRACT_ACCOUNT

## Programs Using This Table
- `z_bapi_mcom_pc_optin==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TIMESTAMP` | CHAR | 14 | 🔑 | Timestamp |
| 3 | `UNIQUE_ID` | CHAR | 32 | 🔑 | GUid of 32 characters |
| 4 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `CHANNEL` | CHAR | 1 |  | Channel |
| 6 | `CONTACT` | CHAR | 100 |  | Contact |
| 7 | `LAST_LOGIN_TIME_STAMP` | CHAR | 14 |  | Last login timestamp |
| 8 | `BINDING_DATE` | DATS | 8 |  | Binding Date |
| 9 | `OTP` | CHAR | 100 |  | OTP |
| 10 | `FIRST_BIND` | CHAR | 1 |  | First_Time_Bind |
| 11 | `VERIFICATION_STATUS` | CHAR | 1 |  | Status |
| 12 | `ERROR_TYPE` | CHAR | 30 |  | Error |
| 13 | `ERROR_CODE` | CHAR | 20 |  | Error Code |
| 14 | `SOURCE` | CHAR | 10 |  | Source |
| 15 | `CREATION_TIME_STAMP` | CHAR | 14 |  | Creation time stamp |
| 16 | `CREATED_BY` | CHAR | 12 |  | Created By |
