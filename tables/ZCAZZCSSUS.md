# ZCAZZCSSUS
**Description:** CSS User Profile Information
**Total Fields:** 55
**Key Fields:** MANDT, CTR_ACC_ID

## Programs Using This Table
- `z_bapi_get_acctinfo===========ft`
- `z_bapi_upd_web_password=======ft`
- `z_bapi_upd_web_profile========ft`
- `z_bapi_webid_create_email=====ft`
- `z_bapi_webpwd_forget==========ft`
- `z_bapi_webpwd_forget_2021pw===ft`
- `z_bapi_webpwd_forget_2021pw_wsft`
- `z_bapi_webpwd_forget_email====ft`
- `z_bapi_webservice_actcode_regeft`
- `z_bapi_webservice_actcode_valift`
- `z_bapi_webservice_ami_create==ft`
- `z_bapi_webservice_change_pass=ft`
- `z_bapi_webservice_id_create===ft`
- `z_bapi_webservice_id_forgottenft`
- `z_bapi_webservice_login=======ft`
- `z_bapi_webservice_login_check=ft`
- `z_bapi_webservice_login_sso===ft`
- `z_bapi_webservice_loginid_exchft`
- `z_bapi_webservice_profile_get=ft`
- `z_bapi_webservice_profile_mtn=ft`
- `z_webservice_update===========ft`
- `zaccount`
- `zcl_ssr_program`
- `zcxt_datamigration_01`
- `zisbi0003`
- `zisbi0014`
- `zisbi0014t`
- `zisbi0067`
- `zisbi0075`
- `zisbi0090`
- `zisbi0144`
- `zisbi0153`
- `zisbi0155`
- `zisbi0156`
- `zisbi0158`
- `zisbi0167`
- `zisbi0167_ami`
- `zisbi0167_bw`
- `zisbi0170`
- `zisbi0171_ptr`
- `zisbi0172_ptr`
- `zisbi0175`
- `ziscrm0009`
- `ziscrm0031`
- `ziscs0004`
- `ziscs0023`
- `ziscs0132`
- `ziscs0151`
- `ziscs0168`
- `ziscs0179`
- `ziscs0195`
- `ziscs0216`
- `ziscs0227`
- `ziscs0245`
- `ziscs0256`
- `ziscs0284`
- `ziscs0288`
- `ziscs0290`
- `ziscs0295`
- `ziscs0297`
- `ziscs0320`
- `ziscs0324`
- `ziscs0329`
- `ziscs0330`
- `ziscs0331`
- `ziscs0333`
- `ziscs0334`
- `ziscs0335`
- `ziscs0338`
- `ziscs0347`
- `ziscs0348`
- `ziscs0349`
- `ziscs0351`
- `ziscs0352`
- `ziscs0366`
- `ziscs0374`
- `ziscs0376`
- `ziscs0377`
- `ziscs0436`
- `ziscs0467`
- `ziscs0480`
- `ziscs0484`
- `ziscs0486`
- `ziscs0845`
- `ziscs1118`
- `ziscs_get_digital_customer`
- `ziscs_migration_account_notif`
- `ziscsmol`
- `ziscv06a`
- `ziscv10`
- `ziscv10nv`
- `zisdm0237`
- `zisdm0275`
- `zisdm0282`
- `zisfi0346`
- `zmasspwupdt`
- `zrca_ssr_cust_extract`
- `ztest_auth_code_2`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CTR_ACC_ID` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `USER_ALIAS` | CHAR | 40 |  | User Alias |
| 4 | `PASSWORD` | CHAR | 32 |  | User Password |
| 5 | `PASSWORD_HINT` | CHAR | 100 |  | User Password Hint |
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
| 20 | `CREATED_BY` | CHAR | 20 |  | Created by |
| 21 | `CREATED_TMST` | CHAR | 14 |  | Created timestamp |
| 22 | `MODIFIED_BY` | CHAR | 20 |  | Modified by |
| 23 | `MODIFIED_TMST` | CHAR | 14 |  | Modified timestamp |
| 24 | `UUID` | CHAR | 32 |  | UUID |
| 25 | `ZZACT_CODE` | CHAR | 10 |  | 10-digit numeric activation code |
| 26 | `ZZACT_DATE` | DATS | 8 |  | Activation date |
| 27 | `EBILL_ATTACH` | CHAR | 1 |  | Ebill Attachment |
| 28 | `NOTE` | CHAR | 2 |  | Note |
| 29 | `EBILL_1_BCOUNT` | INT1 | 3 |  | Ebill email 1 V Bounce counter |
| 30 | `EBILL_1_BDATE` | DATS | 8 |  | Ebill email 1 V last bounced date |
| 31 | `EBILL_2_BCOUNT` | INT1 | 3 |  | Ebill email 2 V Bounce counter |
| 32 | `EBILL_2_BDATE` | DATS | 8 |  | Ebill email 2 V last bounced date |
| 33 | `EBILL_3_BCOUNT` | INT1 | 3 |  | Ebill email 3 V Bounce counter |
| 34 | `EBILL_3_BDATE` | DATS | 8 |  | Ebill email 3 V last bounced date |
| 35 | `EBILL_4_BCOUNT` | INT1 | 3 |  | Ebill email 4 V Bounce counter |
| 36 | `EBILL_4_BDATE` | DATS | 8 |  | Ebill email 4 V last bounced date |
| 37 | `EBILL_5_BCOUNT` | INT1 | 3 |  | Ebill email 5 V Bounce counter |
| 38 | `EBILL_5_BDATE` | DATS | 8 |  | Ebill email 5 V last bounced date |
| 39 | `EBILL_6_BCOUNT` | INT1 | 3 |  | Ebill email 6 V Bounce counter |
| 40 | `EBILL_6_BDATE` | DATS | 8 |  | Ebill email 6 V last bounced date |
| 41 | `TOKEN` | CHAR | 128 |  | Activitation Token |
| 42 | `TOKEN_EXPIRY` | DATS | 8 |  | Token Expiry Date |
| 43 | `TOKEN_VALIDATED` | CHAR | 1 |  | Indicator for validated Token |
| 44 | `EBILL_REMINDER` | CHAR | 2 |  | Green Bill Reminder |
| 45 | `TRIAL_STARTDATE` | DATS | 8 |  | Start date for Green Bill Trial Scheme |
| 46 | `TRIAL_ENDDATE` | DATS | 8 |  | End date for Green Bill Trial Scheme |
| 47 | `TRIAL_STATUS` | CHAR | 1 |  | Status for Green Bill Trial Scheme |
| 48 | `OPTIN` | DATS | 8 |  | OPT In Date |
| 49 | `OPTOUT` | DATS | 8 |  | OPT Out Date |
| 50 | `NONRC` | CHAR | 1 |  | Non-RC A character flag of 'Y' or 'N' |
| 51 | `DEVICE_TOKEN` | CHAR | 255 |  | Device token |
| 52 | `ERECEIPT_ALT` | CHAR | 50 |  | e-Receipt alt. email |
| 53 | `PWD_TOKEN` | CHAR | 128 |  | Work Area Length 128 |
| 54 | `PWD_TOKEN_EXP_DT` | CHAR | 14 |  | Password reset token expiry timestamp |
| 55 | `PWD_CHANGE_DT` | CHAR | 14 |  | Password change timestamp |
