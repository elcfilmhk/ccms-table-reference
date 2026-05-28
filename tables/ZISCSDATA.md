# ZISCSDATA
**Description:** User Data for Webservice Profile Maintenance
**Total Fields:** 35
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_upd_web_profile========ft`
- `z_bapi_webservice_profile_mtn=ft`
- `zcl_z_bapi_upd_web_pro_mpc`
- `zcl_z_bapi_webservi_07_mpc`
- `ziscs0256`
- `ziscs0320`
- `ziscs0329`
- `ziscs0366`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `USER_ALIAS` | CHAR | 40 |  | User Alias |
| 2 | `PASSWORD_HINT` | CHAR | 100 |  | User Password Hint |
| 3 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 4 | `EMAIL_CLPINFO` | CHAR | 1 |  | Receive CLP Info |
| 5 | `EBILL_EMAIL_1` | CHAR | 50 |  | EBill email 1 |
| 6 | `EBILL_EMAIL_2` | CHAR | 50 |  | EBill email 2 |
| 7 | `EBILL_EMAIL_3` | CHAR | 50 |  | EBill email 3 |
| 8 | `EBILL_EMAIL_4` | CHAR | 50 |  | EBill email 4 |
| 9 | `EBILL_EMAIL_5` | CHAR | 50 |  | EBill email 5 |
| 10 | `EBILL_EMAIL_6` | CHAR | 50 |  | EBill email 6 |
| 11 | `LOGIN_FAIL_CNT` | INT1 | 3 |  | Failed login count |
| 12 | `LOGIN_FAIL_TMST` | CHAR | 14 |  | Failed login count timestamp |
| 13 | `EBILL_DEACTIVATION` | CHAR | 1 |  | EBill deactivation flag |
| 14 | `LAST_LOGIN_TMST` | CHAR | 14 |  | Last login timestamp |
| 15 | `ACC_STATUS` | CHAR | 1 |  | Account status |
| 16 | `ACC_DELETION_STATUS` | CHAR | 1 |  | Account deletion status |
| 17 | `UUID` | CHAR | 32 |  | UUID |
| 18 | `EBILL_ATTACH` | CHAR | 1 |  | Ebill Attachment |
| 19 | `NOTE` | CHAR | 2 |  | Note |
| 20 | `EBILL_1_BCOUNT` | INT1 | 3 |  | Ebill email 1 V Bounce counter |
| 21 | `EBILL_1_BDATE` | DATS | 8 |  | Ebill email 1 V last bounced date |
| 22 | `EBILL_2_BCOUNT` | INT1 | 3 |  | Ebill email 2 V Bounce counter |
| 23 | `EBILL_2_BDATE` | DATS | 8 |  | Ebill email 2 V last bounced date |
| 24 | `EBILL_3_BCOUNT` | INT1 | 3 |  | Ebill email 3 V Bounce counter |
| 25 | `EBILL_3_BDATE` | DATS | 8 |  | Ebill email 3 V last bounced date |
| 26 | `EBILL_4_BCOUNT` | INT1 | 3 |  | Ebill email 4 V Bounce counter |
| 27 | `EBILL_4_BDATE` | DATS | 8 |  | Ebill email 4 V last bounced date |
| 28 | `EBILL_5_BCOUNT` | INT1 | 3 |  | Ebill email 5 V Bounce counter |
| 29 | `EBILL_5_BDATE` | DATS | 8 |  | Ebill email 5 V last bounced date |
| 30 | `EBILL_6_BCOUNT` | INT1 | 3 |  | Ebill email 6 V Bounce counter |
| 31 | `EBILL_6_BDATE` | DATS | 8 |  | Ebill email 6 V last bounced date |
| 32 | `EBILL_REMINDER` | CHAR | 2 |  | Green Bill Reminder |
| 33 | `TRIAL_STARTDATE` | DATS | 8 |  | Start date for Green Bill Trial Scheme |
| 34 | `TRIAL_ENDDATE` | DATS | 8 |  | End date for Green Bill Trial Scheme |
| 35 | `TRIAL_STATUS` | CHAR | 1 |  | Status for Green Bill Trial Scheme |
