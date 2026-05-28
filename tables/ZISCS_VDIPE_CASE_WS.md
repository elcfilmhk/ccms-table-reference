# ZISCS_VDIPE_CASE_WS
**Description:** In/Output Struct for ZISCS_VDIPE_CASE via WebService
**Total Fields:** 57
**Key Fields:** _none_

## Programs Using This Table
- `z_vdip_enq_get_cases==========ft`
- `z_vdip_enq_get_cases_ws=======ft`
- `z_vdip_enq_save_cases_ws======ft`
- `zcl_z_vdip_enq_save_ca_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CASE_ID` | NUMC | 8 |  | VoltDipEnquiry case ID |
| 2 | `CREATOR_TYPE` | CHAR | 10 |  | Type of Case Creator |
| 3 | `CREATE_USER` | CHAR | 12 |  | Username who created the case |
| 4 | `CREATE_DT` | CHAR | 14 |  | Create datetime [Format: YYYYMMDDhhmmss] |
| 5 | `CASE_REP_DT` | CHAR | 14 |  | Reported Case datetime [Format: YYYYMMDDhhmmss] |
| 6 | `CASE_REMARK` | CHAR | 500 |  | Remark during case creation |
| 7 | `STR_ERG2` | CHAR | 40 |  | Street 3 |
| 8 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 9 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 10 | `STREET` | CHAR | 60 |  | Street |
| 11 | `CITY2` | CHAR | 40 |  | District |
| 12 | `CITY1` | CHAR | 40 |  | City |
| 13 | `FULL_ADDR` | CHAR | 300 |  | All Address fields concatenated |
| 14 | `ACC_MGR_USER` | CHAR | 12 |  | Username of Account Manager |
| 15 | `CASE_TYPE` | CHAR | 4 |  | 'I': Type I cases; "II": Type II cases; etc |
| 16 | `LAST_CHANGE_DT` | CHAR | 14 |  | Changed Datetime |
| 17 | `LAST_CHANGE_USER` | CHAR | 12 |  | Changed By |
| 18 | `REPLYCHANNEL` | CHAR | 10 |  | Reply Channel |
| 19 | `REPLY_LANG` | LANG | 1 |  | Language Key |
| 20 | `STATUS` | CHAR | 1 |  | VoltDipEnquiry case Status |
| 21 | `COMPLETE_DT` | CHAR | 14 |  | Complete datetime [Format: YYYYMMDDhhmmss] |
| 22 | `COMPLETE_USER` | CHAR | 12 |  | Username who completed the case |
| 23 | `CANCEL_DT` | CHAR | 14 |  | Cancel datetime [Format: YYYYMMDDhhmmss] |
| 24 | `CANCEL_USER` | CHAR | 12 |  | Username who cancelled the case |
| 25 | `INCD_VOLT_LV` | CHAR | 10 |  | Investigation Result: Voltage Level |
| 26 | `INCD_DT` | CHAR | 14 |  | Investigation Result: Incident datetime |
| 27 | `INCD_CAUSE_CODE` | CHAR | 1 |  | Investigation Result: Incident Cause Code |
| 28 | `INCD_CAUSE_DESC` | CHAR | 500 |  | Investigation Result: Incident Cause Description |
| 29 | `INCD_ID_DT` | CHAR | 14 |  | Investigation Result datetime [Format: YYYYMMDDhhmmss] |
| 30 | `INCD_ID_USER` | CHAR | 12 |  | Investigation Result by User |
| 31 | `LTTR_REF` | CHAR | 80 |  | Reference Number as displayed on letter |
| 32 | `LTTR_RCPT_NAME` | CHAR | 100 |  | Recipient Name as displayed on letter |
| 33 | `LTTR_SUBJ_MODE` | CHAR | 1 |  | Letter Subject Header Mode |
| 34 | `LTTR_SUBJ_TEXT` | CHAR | 200 |  | Letter Subject Header Text |
| 35 | `LTTR_SUBJ_OTH_TEXT` | CHAR | 200 |  | Letter Other Subject Header Text |
| 36 | `LTTR_ACC_MGR_NAME` | CHAR | 100 |  | AM name as displayed on letter |
| 37 | `LTTR_ACC_MGR_TEL` | CHAR | 30 |  | AM Telephone as displayed on letter |
| 38 | `SENT_LTTR_COUNT` | INT2 | 5 |  | No of letters sent |
| 39 | `LAST_SENT_DT` | CHAR | 14 |  | Letter Last sent Datetime |
| 40 | `SERV_PLED_DT` | CHAR | 14 |  | Service Pledge deadline datetime |
| 41 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 42 | `CUSTOMER_NAME` | CHAR | 100 |  | Customer Name |
| 43 | `COMP_NAME` | CHAR | 100 |  | Company Name of customer |
| 44 | `CUST_ADDR_SAME` | CHAR | 1 |  | 'Y': Same as Affected Address; 'N': Otherwise |
| 45 | `CUST_STR_ERG2` | CHAR | 40 |  | Street 3 |
| 46 | `CUST_STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 47 | `CUST_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 48 | `CUST_STREET` | CHAR | 60 |  | Street |
| 49 | `CUST_CITY2` | CHAR | 40 |  | District |
| 50 | `CUST_CITY1` | CHAR | 40 |  | City |
| 51 | `CUST_FULL_ADDR` | CHAR | 300 |  | All Address fields concatenated |
| 52 | `CUST_TEL` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 53 | `CUST_FAX` | CHAR | 30 |  | First fax no.: dialling code+number |
| 54 | `CUST_EMAIL` | CHAR | 200 |  | Customer Email Address |
| 55 | `CUST_SEARCH` | CHAR | 1 |  | 'Y': Customer address searchable; 'N': otherwise |
| 56 | `WORKDATE_COMP` | NUMC | 8 |  | Work Date of Case Completion |
| 57 | `WORKDATE_0` | NUMC | 8 |  | Work Date 0 (ie. Creation Work Date) |
