# ZFI_LOGGING_RPT
**Description:** Report for UI Logging
**Total Fields:** 21
**Key Fields:** MANDT, SYSID, TA_ID

## Programs Using This Table
- `zisfi0309`
- `zisfi0343`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | ABAP System Field: Name of SAP System |
| 3 | `TA_ID` | CHAR | 40 | 🔑 | Session ID of Taskhandler |
| 4 | `USERNAME` | CHAR | 12 |  | User Name |
| 5 | `DATE_FROM` | DATS | 8 |  | ABAP System Field: Current Date of Application Server |
| 6 | `FROM_TIME` | TIMS | 6 |  | ABAP System Field: Current Time of Application Server |
| 7 | `DATE_TO` | DATS | 8 |  | ABAP System Field: Current Date of Application Server |
| 8 | `TO_TIME` | TIMS | 6 |  | ABAP System Field: Current Time of Application Server |
| 9 | `TCODE` | CHAR | 20 |  | Transaction Code |
| 10 | `TCODE2` | CHAR | 20 |  | Client-Side Transaction Code |
| 11 | `INPUT_DATA_TYPE` | CHAR | 100 |  | Input Data Type (separate by |) |
| 12 | `INPUT_VALUE` | CHAR | 100 |  | Input Value (separate by | for another type, separate by ; ) |
| 13 | `NO_OF_CA` | NUMC | 10 |  | No. of unique CA in the output |
| 14 | `NO_OF_BP` | NUMC | 10 |  | No. of unique BP in the output |
| 15 | `ID` | CHAR | 1 |  | 'X' if the output display ID (i.e. HKID) |
| 16 | `CREDIT_CARD` | CHAR | 1 |  | 'X' if the output display Credit Card No |
| 17 | `BANK_ACCOUNT` | CHAR | 1 |  | 'X' if the output display Bank Account No |
| 18 | `DATE_OF_BIRTH` | CHAR | 1 |  | 'X' if the output display Date of Birth |
| 19 | `EMAIL` | CHAR | 1 |  | 'X' if the output display Email |
| 20 | `CONTACT_NO` | CHAR | 1 |  | 'X' if the output display Contact No |
| 21 | `NAME` | CHAR | 1 |  | 'X' if the output display Name |
