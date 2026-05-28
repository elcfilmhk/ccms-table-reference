# ZCREATECA
**Description:** Automated Move-in details
**Total Fields:** 138
**Key Fields:** MANDT, TXNNUM

## Programs Using This Table
- `ziscs0256`
- `ziscs0257`
- `ziscs0259`
- `ziscs0260`
- `ziscs0261`
- `ziscs0270`
- `ziscs0299`
- `ziscs0301`
- `ziscs0309`
- `ziscs0361`
- `ziscs1131`
- `ziscs1133`
- `ziscs1136`
- `ziscs_sms02`
- `ziscssmsr1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `VSTELLE` | CHAR | 10 |  | Premise |
| 4 | `HAUS` | CHAR | 30 |  | Connection Object |
| 5 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 6 | `ACCTCLASS` | CHAR | 4 |  | Acc. class |
| 7 | `BANKACCT` | CHAR | 18 |  | Bank account number |
| 8 | `BANKKEY` | CHAR | 15 |  | Bank Keys |
| 9 | `BANKBRANCHNO` | CHAR | 3 |  | Bank Branch No. |
| 10 | `CONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 11 | `CONTRACT` | CHAR | 10 |  | Contract |
| 12 | `MOVEINDOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 13 | `MOVEOUTDOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 14 | `ACCTHOLDERID1` | CHAR | 60 |  | Autopay account holder 1 ID |
| 15 | `ACCTHOLDERID2` | CHAR | 60 |  | Autopay account holder 2 ID |
| 16 | `ACCTHOLDERID1TYP` | CHAR | 6 |  | Autopay account holder 1 ID type |
| 17 | `ACCTHOLDERID2TYP` | CHAR | 6 |  | Autopay account holder 2 ID Type |
| 18 | `ACCTHOLDERNAME1` | CHAR | 80 |  | Autopay account holder 1 name |
| 19 | `ACCTHOLDERNAME2` | CHAR | 80 |  | Autopay account holder 2 name |
| 20 | `AUTOPAY` | CHAR | 1 |  | Apply for autopay |
| 21 | `AUTOPAY_HANDLE` | CHAR | 1 |  | Autopay handled |
| 22 | `EMAIL_SMS` | CHAR | 5 |  | Email or SMS |
| 23 | `EBILL_SEL` | CHAR | 1 |  | Green Bill selected |
| 24 | `EBILL1` | CHAR | 60 |  | eBill email address 1 |
| 25 | `EBILL2` | CHAR | 60 |  | eBill email address 2 |
| 26 | `EBILL3` | CHAR | 60 |  | eBill email address 3 |
| 27 | `EBILL4` | CHAR | 60 |  | eBill email address 4 |
| 28 | `EBILL5` | CHAR | 60 |  | eBill email address 5 |
| 29 | `EBILL6` | CHAR | 60 |  | eBill email address 6 |
| 30 | `TC_ACCEPT` | CHAR | 1 |  | Accept Terms and Condition |
| 31 | `RATECAT` | CHAR | 10 |  | Rate category |
| 32 | `AREA` | CHAR | 9 |  | Area of Premise |
| 33 | `AREAUNIT` | CHAR | 10 |  | Unit of Area |
| 34 | `CONTACTNUM` | CHAR | 8 |  | Contact Phone No. |
| 35 | `EXTENSION` | CHAR | 4 |  | Extension |
| 36 | `MOBILENUM` | CHAR | 8 |  | Mobile No. |
| 37 | `FAXNUM` | CHAR | 8 |  | Fax No. |
| 38 | `EMAIL` | CHAR | 60 |  | Email Address |
| 39 | `SUPPLYADDR` | CHAR | 100 |  | Supply Address |
| 40 | `POSTALADDR` | CHAR | 100 |  | Postal Address |
| 41 | `CITY` | CHAR | 40 |  | City |
| 42 | `CO` | CHAR | 40 |  | c/o name |
| 43 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 44 | `DISTRICT` | CHAR | 40 |  | District |
| 45 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 46 | `HSE_NUM` | CHAR | 10 |  | House Number |
| 47 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 48 | `ROOM` | CHAR | 10 |  | Room or Apartment Number |
| 49 | `STREET` | CHAR | 60 |  | Street |
| 50 | `STREET2` | CHAR | 40 |  | Street 2 |
| 51 | `STREET3` | CHAR | 40 |  | Street 3 |
| 52 | `BP_NAME_ENG` | CHAR | 80 |  | Business Partner Name (English) |
| 53 | `BP_NAME_CHI` | CHAR | 60 |  | Business Partner Name (Chinese) |
| 54 | `BP_ID_TYPE` | CHAR | 6 |  | BP ID Type |
| 55 | `BP_ID_NUM` | CHAR | 60 |  | BP ID No. |
| 56 | `POSTAL` | CHAR | 3 |  | Postal address Indicator |
| 57 | `PHASE` | CHAR | 10 |  | 2 / 3 Phase meter |
| 58 | `SEX` | CHAR | 1 |  | Sex of BP |
| 59 | `LAST_MR_DATE` | DATS | 8 |  | Last meter reading date |
| 60 | `MR` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 61 | `METER` | CHAR | 18 |  | Meter installed |
| 62 | `MI_DATE` | DATS | 8 |  | Move-in date |
| 63 | `ACCEPT_LAST_READ` | CHAR | 1 |  | Accept last reading ind. (Y/N) |
| 64 | `PREMISE_VALID` | CHAR | 1 |  | Premise validation |
| 65 | `BP_VALID` | CHAR | 1 |  | BP validation |
| 66 | `SUPPLYTYPE` | CHAR | 5 |  | Type of supply |
| 67 | `STATUS` | CHAR | 1 |  | Record Status (A, S, R, C, X) |
| 68 | `TYPE` | CHAR | 2 |  | Record Type (MI) |
| 69 | `SOURCE` | CHAR | 1 |  | Record Source (C - CLP Online) |
| 70 | `REMARK` | CHAR | 100 |  | Remark |
| 71 | `ASSIGNTO` | CHAR | 12 |  | User Name |
| 72 | `CREATIONDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 73 | `CREATIONDATETIME` | CHAR | 14 |  | Time Stamp |
| 74 | `LASTCHANGEDATE` | DATS | 8 |  | Date of Last Change |
| 75 | `LASTCHANGEDATETIME` | CHAR | 14 |  | Time Stamp |
| 76 | `LASTCHANGEBY` | CHAR | 12 |  | Name of person who changed object |
| 77 | `DUEDATE` | DATS | 8 |  | Due Date |
| 78 | `TASK_STATUS` | CHAR | 1 |  | Status of the Task created in the Task Management |
| 79 | `RECIPIENT` | CHAR | 60 |  | Recipient email address |
| 80 | `ADDRPROOFUPLOAD` | CHAR | 1 |  | Status of address proof upload |
| 81 | `ADDRPROOFREQ` | CHAR | 1 |  | Address proof request status |
| 82 | `MI_DOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 83 | `MO_DOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 84 | `AMP` | CHAR | 5 |  | Ampere |
| 85 | `TITLE` | CHAR | 5 |  | Customer Title |
| 86 | `TEMP_ACCT_FROM` | DATS | 8 |  | Temp supply from date |
| 87 | `TEMP_ACCT_TO` | DATS | 8 |  | Temp supply to date |
| 88 | `AUTOPAYCANC` | CHAR | 1 |  | Autopay cancellation status |
| 89 | `SMSNUM` | CHAR | 8 |  | SMS number |
| 90 | `EFFDATE` | DATS | 8 |  | MI Effective date |
| 91 | `LANGU` | LANG | 1 |  | Language Key |
| 92 | `TRADECLASS` | CHAR | 30 |  | Trade Class |
| 93 | `SUBMIT_DATE` | DATS | 8 |  | Move-in submission date |
| 94 | `SUBMIT_DATETIME` | CHAR | 14 |  | Time Stamp |
| 95 | `FMOREQ` | CHAR | 1 |  | Forced move-out request status |
| 96 | `PURECA` | CHAR | 1 |  | Pure CA |
| 97 | `FMOBY` | CHAR | 12 |  | Force MO Created By |
| 98 | `FMOON` | DATS | 8 |  | Force MO Created On |
| 99 | `ZZTRADE_CAT` | CHAR | 2 |  | Trade category |
| 100 | `ZZTRADE_CLASS` | CHAR | 10 |  | Trade |
| 101 | `ZZPREM_FUNC` | CHAR | 3 |  | Premise function |
| 102 | `PMO` | CHAR | 1 |  | Pending move-out |
| 103 | `CHKNAME` | CHAR | 1 |  | Check BP name |
| 104 | `ACTION` | CHAR | 1 |  | Action |
| 105 | `MO_TXN` | CHAR | 10 |  | Move-out Transaction no. |
| 106 | `GB_TRIAL_SCHEME` | CHAR | 1 |  | GB Trial Scheme |
| 107 | `ALLOW_MI` | CHAR | 1 |  | Allow MI flag |
| 108 | `CONSENT` | CHAR | 1 |  | Consent |
| 109 | `APP_TYPE` | CHAR | 1 |  | Application Type (Applicant - 'T' / Authorized Rep - 'A') |
| 110 | `AR_NAME` | CHAR | 80 |  | Agent name |
| 111 | `AR_COMP` | CHAR | 80 |  | Agent company |
| 112 | `AR_MOBN` | CHAR | 8 |  | Agent mobile phone |
| 113 | `AR_EMAIL` | CHAR | 60 |  | Agent email |
| 114 | `DOC_STATUS` | CHAR | 1 |  | Document Submission flag/indicator (Later/Submitted) |
| 115 | `HKID_SUBMIT` | CHAR | 1 |  | HKID Submission Status |
| 116 | `ECO_POINT_TRANSFER` | CHAR | 1 |  | Eco points transferred/ Not transferred indicator |
| 117 | `CIAMID` | CHAR | 50 |  | CIAM ID |
| 118 | `MKT_EMAIL` | CHAR | 60 |  | Marketing  Email |
| 119 | `MKT_PHONE` | CHAR | 10 |  | Marketing Phone |
| 120 | `DOC_URL1` | CHAR | 120 |  | Document URL for identification |
| 121 | `DOC_URL2` | CHAR | 600 |  | Document URL for Address |
| 122 | `ACCEPT_BALANCE` | CHAR | 1 |  | Accept the last balance |
| 123 | `OP_NAME` | CHAR | 40 |  | Operator name |
| 124 | `OP_CONTACT` | CHAR | 50 |  | Operator contact infomation |
| 125 | `BKVID` | CHAR | 4 |  | Bank details ID |
| 126 | `REQUIRED_UPLOAD_ID` | CHAR | 1 |  | Required upload ID(X :YES,  :NO) |
| 127 | `REQUIRED_UPLOAD_DOC` | CHAR | 1 |  | Required upload DOC(X :YES,  :NO) |
| 128 | `IS_CLIENT_SUBMIT` | CHAR | 1 |  | Is client submit(X :YES,  :NO) |
| 129 | `INACTIVE_CONSUMPTION` | CHAR | 1 |  | Inactive consumption |
| 130 | `IS_REJECT_DOC` | CHAR | 1 |  | Is reject doc(X :YES,  :NO) |
| 131 | `SUBMIT_DOC_DATE` | DATS | 8 |  | Submit document date |
| 132 | `RESUBMIT_DOC_DATE` | DATS | 8 |  | Resubmit doc date |
| 133 | `AGENT_SUBMIT_DATE` | DATS | 8 |  | Agent submit date |
| 134 | `EDGE_CASE` | CHAR | 20 |  | Edge Case |
| 135 | `REJECT_DATE_TIME` | CHAR | 14 |  | Time Stamp |
| 136 | `AGENT_MI_COMPLETE_DATETIME` | CHAR | 14 |  | Time Stamp |
| 137 | `UPD_TXN` | CHAR | 10 |  | latest CRM activity id |
| 138 | `NON_AMI_UPLOAD_DOC` | CHAR | 1 |  | Non AMI Upload Document flag('X' for Yes, '' for No) |
