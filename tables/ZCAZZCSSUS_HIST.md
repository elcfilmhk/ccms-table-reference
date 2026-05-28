# ZCAZZCSSUS_HIST
**Description:** CSS User Profile Information History
**Total Fields:** 44
**Key Fields:** MANDT, CTR_ACC_ID, CREATED_BY, CREATED_TMST

## Programs Using This Table
- `ziscs0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CTR_ACC_ID` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CREATED_BY` | CHAR | 20 | 🔑 | Created by |
| 4 | `CREATED_TMST` | CHAR | 14 | 🔑 | Created timestamp |
| 5 | `USER_ALIAS` | CHAR | 40 |  | User Alias |
| 6 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 7 | `EMAIL_CLPINFO` | CHAR | 1 |  | Receive CLP Info |
| 8 | `EBILL_EMAIL_1` | CHAR | 50 |  | EBill email 1 |
| 9 | `EBILL_EMAIL_2` | CHAR | 50 |  | EBill email 2 |
| 10 | `EBILL_EMAIL_3` | CHAR | 50 |  | EBill email 3 |
| 11 | `EBILL_EMAIL_4` | CHAR | 50 |  | EBill email 4 |
| 12 | `EBILL_EMAIL_5` | CHAR | 50 |  | EBill email 5 |
| 13 | `EBILL_EMAIL_6` | CHAR | 50 |  | EBill email 6 |
| 14 | `LOGIN_FAIL_CNT` | INT1 | 3 |  | Failed login count |
| 15 | `LOGIN_FAIL_TMST` | CHAR | 14 |  | Failed login count timestamp |
| 16 | `EBILL_DEACTIVATE` | CHAR | 1 |  | EBill deactivation flag |
| 17 | `LAST_LOGIN_TMST` | CHAR | 14 |  | Last login timestamp |
| 18 | `STATUS` | CHAR | 1 |  | Account status |
| 19 | `ACCOUNT_DELETE` | CHAR | 1 |  | Account deletion status |
| 20 | `UUID` | CHAR | 32 |  | UUID |
| 21 | `ZZACT_CODE` | CHAR | 10 |  | 10-digit numeric activation code |
| 22 | `ZZACT_DATE` | DATS | 8 |  | Activation date |
| 23 | `EBILL_ATTACH` | CHAR | 1 |  | Ebill Attachment |
| 24 | `NOTE` | CHAR | 2 |  | Note |
| 25 | `EBILL_1_BCOUNT` | INT1 | 3 |  | Ebill email 1 V Bounce counter |
| 26 | `EBILL_1_BDATE` | DATS | 8 |  | Ebill email 1 V last bounced date |
| 27 | `EBILL_2_BCOUNT` | INT1 | 3 |  | Ebill email 2 V Bounce counter |
| 28 | `EBILL_2_BDATE` | DATS | 8 |  | Ebill email 2 V last bounced date |
| 29 | `EBILL_3_BCOUNT` | INT1 | 3 |  | Ebill email 3 V Bounce counter |
| 30 | `EBILL_3_BDATE` | DATS | 8 |  | Ebill email 3 V last bounced date |
| 31 | `EBILL_4_BCOUNT` | INT1 | 3 |  | Ebill email 4 V Bounce counter |
| 32 | `EBILL_4_BDATE` | DATS | 8 |  | Ebill email 4 V last bounced date |
| 33 | `EBILL_5_BCOUNT` | INT1 | 3 |  | Ebill email 5 V Bounce counter |
| 34 | `EBILL_5_BDATE` | DATS | 8 |  | Ebill email 5 V last bounced date |
| 35 | `EBILL_6_BCOUNT` | INT1 | 3 |  | Ebill email 6 V Bounce counter |
| 36 | `EBILL_6_BDATE` | DATS | 8 |  | Ebill email 6 V last bounced date |
| 37 | `ACTION` | CHAR | 1 |  | Action |
| 38 | `EBILL_REMINDER` | CHAR | 2 |  | Green Bill Reminder |
| 39 | `TRIAL_STARTDATE` | DATS | 8 |  | Start date for Green Bill Trial Scheme |
| 40 | `TRIAL_ENDDATE` | DATS | 8 |  | End date for Green Bill Trial Scheme |
| 41 | `TRIAL_STATUS` | CHAR | 1 |  | Status for Green Bill Trial Scheme |
| 42 | `OPTIN` | DATS | 8 |  | OPT In Date |
| 43 | `OPTOUT` | DATS | 8 |  | OPT Out Date |
| 44 | `NONRC` | CHAR | 1 |  | Non-RC A character flag of 'Y' or 'N' |
