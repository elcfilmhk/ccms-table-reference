# ZCS_MI_DETAIL
**Description:** Struct for MI Detail data
**Total Fields:** 118
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_ciamid_mi_detail=======ft`
- `z_bapi_update_mi_record=======ft`
- `zcl_z_bapi_update_mi_r_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 2 | `VSTELLE` | CHAR | 10 |  | Premise |
| 3 | `HAUS` | CHAR | 30 |  | Connection Object |
| 4 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 5 | `ACCTCLASS` | CHAR | 4 |  | Acc. class |
| 6 | `CONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 7 | `CONTRACT` | CHAR | 10 |  | Contract |
| 8 | `MOVEINDOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 9 | `MOVEOUTDOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 10 | `EMAIL_SMS` | CHAR | 5 |  | Email or SMS |
| 11 | `AREA` | CHAR | 9 |  | Area of Premise |
| 12 | `AREAUNIT` | CHAR | 10 |  | Unit of Area |
| 13 | `CONTACTNUM` | CHAR | 8 |  | Contact Phone No. |
| 14 | `EXTENSION` | CHAR | 4 |  | Extension |
| 15 | `MOBILENUM` | CHAR | 8 |  | Mobile No. |
| 16 | `FAXNUM` | CHAR | 8 |  | Fax No. |
| 17 | `EMAIL` | CHAR | 60 |  | Email Address |
| 18 | `SUPPLYADDR` | CHAR | 100 |  | Supply Address |
| 19 | `POSTALADDR` | CHAR | 100 |  | Postal Address |
| 20 | `CITY` | CHAR | 40 |  | City |
| 21 | `CO` | CHAR | 40 |  | c/o name |
| 22 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 23 | `DISTRICT` | CHAR | 40 |  | District |
| 24 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 25 | `HSE_NUM` | CHAR | 10 |  | House Number |
| 26 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 27 | `ROOM` | CHAR | 10 |  | Room or Apartment Number |
| 28 | `STREET` | CHAR | 60 |  | Street |
| 29 | `STREET2` | CHAR | 40 |  | Street 2 |
| 30 | `STREET3` | CHAR | 40 |  | Street 3 |
| 31 | `BP_NAME_ENG` | CHAR | 80 |  | Business Partner Name (English) |
| 32 | `BP_NAME_CHI` | CHAR | 60 |  | Business Partner Name (Chinese) |
| 33 | `BP_ID_TYPE` | CHAR | 6 |  | BP ID Type |
| 34 | `BP_ID_NUM` | CHAR | 60 |  | BP ID No. |
| 35 | `POSTAL` | CHAR | 3 |  | Postal address Indicator |
| 36 | `PHASE` | CHAR | 10 |  | 2 / 3 Phase meter |
| 37 | `SEX` | CHAR | 1 |  | Sex of BP |
| 38 | `LAST_MR_DATE` | DATS | 8 |  | Last meter reading date |
| 39 | `MR` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 40 | `METER` | CHAR | 18 |  | Meter installed |
| 41 | `MI_DATE` | DATS | 8 |  | Move-in date |
| 42 | `ACCEPT_LAST_READ` | CHAR | 1 |  | Accept last reading ind. (Y/N) |
| 43 | `PREMISE_VALID` | CHAR | 1 |  | Premise validation |
| 44 | `BP_VALID` | CHAR | 1 |  | BP validation |
| 45 | `SUPPLYTYPE` | CHAR | 5 |  | Type of supply |
| 46 | `STATUS` | CHAR | 1 |  | Record Status (A, S, R, C, X) |
| 47 | `TYPE` | CHAR | 2 |  | Record Type (MI) |
| 48 | `SOURCE` | CHAR | 1 |  | Record Source (C - CLP Online) |
| 49 | `REMARK` | CHAR | 100 |  | Remark |
| 50 | `ASSIGNTO` | CHAR | 12 |  | User Name |
| 51 | `CREATIONDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 52 | `CREATIONDATETIME` | CHAR | 14 |  | Time Stamp |
| 53 | `LASTCHANGEDATE` | DATS | 8 |  | Date of Last Change |
| 54 | `LASTCHANGEDATETIME` | CHAR | 14 |  | Time Stamp |
| 55 | `LASTCHANGEBY` | CHAR | 12 |  | Name of person who changed object |
| 56 | `DUEDATE` | DATS | 8 |  | Due Date |
| 57 | `TASK_STATUS` | CHAR | 1 |  | Status of the Task created in the Task Management |
| 58 | `RECIPIENT` | CHAR | 60 |  | Recipient email address |
| 59 | `ADDRPROOFUPLOAD` | CHAR | 1 |  | Status of address proof upload |
| 60 | `ADDRPROOFREQ` | CHAR | 1 |  | Address proof request status |
| 61 | `MI_DOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 62 | `MO_DOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 63 | `AMP` | CHAR | 5 |  | Ampere |
| 64 | `TITLE` | CHAR | 5 |  | Customer Title |
| 65 | `TEMP_ACCT_FROM` | DATS | 8 |  | Temp supply from date |
| 66 | `TEMP_ACCT_TO` | DATS | 8 |  | Temp supply to date |
| 67 | `SMSNUM` | CHAR | 8 |  | SMS number |
| 68 | `EFFDATE` | DATS | 8 |  | MI Effective date |
| 69 | `LANGU` | LANG | 1 |  | Language Key |
| 70 | `SUBMIT_DATE` | DATS | 8 |  | Move-in submission date |
| 71 | `SUBMIT_DATETIME` | CHAR | 14 |  | Time Stamp |
| 72 | `FMOREQ` | CHAR | 1 |  | Forced move-out request status |
| 73 | `PURECA` | CHAR | 1 |  | Pure CA |
| 74 | `FMOBY` | CHAR | 12 |  | Force MO Created By |
| 75 | `FMOON` | DATS | 8 |  | Force MO Created On |
| 76 | `ZZTRADE_CAT` | CHAR | 2 |  | Trade category |
| 77 | `ZZTRADE_CLASS` | CHAR | 10 |  | Trade |
| 78 | `ZZPREM_FUNC` | CHAR | 3 |  | Premise function |
| 79 | `PMO` | CHAR | 1 |  | Pending move-out |
| 80 | `CHKNAME` | CHAR | 1 |  | Check BP name |
| 81 | `ACTION` | CHAR | 1 |  | Action |
| 82 | `MO_TXN` | CHAR | 10 |  | Move-out Transaction no. |
| 83 | `ALLOW_MI` | CHAR | 1 |  | Allow MI flag |
| 84 | `CONSENT` | CHAR | 1 |  | Consent |
| 85 | `APP_TYPE` | CHAR | 1 |  | Application Type (Applicant - 'T' / Authorized Rep - 'A') |
| 86 | `AR_NAME` | CHAR | 80 |  | Agent name |
| 87 | `AR_COMP` | CHAR | 80 |  | Agent company |
| 88 | `AR_MOBN` | CHAR | 8 |  | Agent mobile phone |
| 89 | `AR_EMAIL` | CHAR | 60 |  | Agent email |
| 90 | `DOC_STATUS` | CHAR | 1 |  | Document Submission flag/indicator (Later/Submitted) |
| 91 | `HKID_SUBMIT` | CHAR | 1 |  | HKID Submission Status |
| 92 | `ECO_POINT_TRANSFER` | CHAR | 1 |  | Eco points transferred/ Not transferred indicator |
| 93 | `CIAMID` | CHAR | 50 |  | CIAM ID |
| 94 | `MKT_EMAIL` | CHAR | 60 |  | Marketing  Email |
| 95 | `MKT_PHONE` | CHAR | 10 |  | Marketing Phone |
| 96 | `DOC_URL1` | CHAR | 120 |  | Document URL for identification |
| 97 | `DOC_URL2` | CHAR | 600 |  | Document URL for Address |
| 98 | `ACCEPT_BALANCE` | CHAR | 1 |  | Accept the last balance |
| 99 | `OP_NAME` | CHAR | 40 |  | Operator name |
| 100 | `OP_CONTACT` | CHAR | 50 |  | Operator contact infomation |
| 101 | `BKVID` | CHAR | 4 |  | Bank details ID |
| 102 | `REQUIRED_UPLOAD_ID` | CHAR | 1 |  | Required upload ID(X :YES,  :NO) |
| 103 | `REQUIRED_UPLOAD_DOC` | CHAR | 1 |  | Required upload DOC(X :YES,  :NO) |
| 104 | `IS_CLIENT_SUBMIT` | CHAR | 1 |  | Is client submit(X :YES,  :NO) |
| 105 | `INACTIVE_CONSUMPTION` | CHAR | 1 |  | Inactive consumption |
| 106 | `IS_REJECT_DOC` | CHAR | 1 |  | Is reject doc(X :YES,  :NO) |
| 107 | `SUBMIT_DOC_DATE` | DATS | 8 |  | Submit document date |
| 108 | `RESUBMIT_DOC_DATE` | DATS | 8 |  | Resubmit doc date |
| 109 | `AGENT_SUBMIT_DATE` | DATS | 8 |  | Agent submit date |
| 110 | `EDGE_CASE` | CHAR | 20 |  | Edge Case |
| 111 | `RATECAT` | CHAR | 10 |  | Rate category |
| 112 | `CASE_TYPE` | CHAR | 20 |  | Case Type |
| 113 | `REJECT_DATE_TIME` | CHAR | 14 |  | Time Stamp |
| 114 | `AGENT_MI_COMPLETE_DATETIME` | CHAR | 14 |  | Time Stamp |
| 115 | `EBILL1` | CHAR | 60 |  | eBill email address 1 |
| 116 | `LIGHT` | CHAR | 20 |  | Light of move-in task |
| 117 | `UPD_TXN` | CHAR | 10 |  | latest CRM activity id |
| 118 | `NON_AMI_UPLOAD_DOC` | CHAR | 1 |  | Non AMI Upload Document flag('X' for Yes, '' for No) |
