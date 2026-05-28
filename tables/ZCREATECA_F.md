# ZCREATECA_F
**Description:** Automated Move-in details (Fax and Letter)
**Total Fields:** 135
**Key Fields:** MANDT, TXNNUM

## Programs Using This Table
- `ziscs0260_f`
- `ziscs0261`
- `ziscs0297`
- `ziscs0299`
- `ziscs0309`
- `ziscs0315`
- `ziscs0317`

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
| 10 | `CONTRACTACCT_OLD` | CHAR | 12 |  | Contract Account Number |
| 11 | `CONTRACT_OLD` | CHAR | 10 |  | Contract |
| 12 | `CONTRACTACCT_NEW` | CHAR | 12 |  | Contract Account Number |
| 13 | `CONTRACT_NEW` | CHAR | 10 |  | Contract |
| 14 | `MOVEINDOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 15 | `MOVEOUTDOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 16 | `BP_NAME_ENG1` | CHAR | 80 |  | Business Partner Name (English) |
| 17 | `BP_NAME_ENG2` | CHAR | 80 |  | Business Partner Name (English) |
| 18 | `BP_NAME_CHI` | CHAR | 60 |  | Business Partner Name (Chinese) |
| 19 | `BP_ID_NUM` | CHAR | 60 |  | BP ID No. |
| 20 | `BP_ID_TYPE` | CHAR | 6 |  | BP ID Type |
| 21 | `ID_PROOF` | CHAR | 1 |  | Identity Proof Checked |
| 22 | `CONTACTNUM_O` | CHAR | 8 |  | Contact Phone No. |
| 23 | `EXT_O` | CHAR | 4 |  | Extension |
| 24 | `CONTACTNUM_N` | CHAR | 8 |  | Contact Phone No. |
| 25 | `EXT_N` | CHAR | 4 |  | Extension |
| 26 | `CONTACTNUM_OTHER` | CHAR | 8 |  | Contact Phone No. |
| 27 | `EXT_OTHER` | CHAR | 4 |  | Extension |
| 28 | `MOBILENUM` | CHAR | 8 |  | Mobile No. |
| 29 | `FAXNUM` | CHAR | 8 |  | Fax No. |
| 30 | `EMAIL1` | CHAR | 60 |  | Email Address |
| 31 | `EMAIL2` | CHAR | 60 |  | Email Address |
| 32 | `LANGU` | LANG | 1 |  | Language Key |
| 33 | `BMETHOD` | CHAR | 1 |  | Billing Method |
| 34 | `SUPPLYADDR` | CHAR | 100 |  | Supply Address |
| 35 | `POSTALADDR` | CHAR | 100 |  | Postal Address |
| 36 | `CITY` | CHAR | 40 |  | City |
| 37 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 38 | `DISTRICT` | CHAR | 40 |  | District |
| 39 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 40 | `HSE_NUM` | CHAR | 10 |  | House Number |
| 41 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 42 | `ROOM` | CHAR | 10 |  | Room or Apartment Number |
| 43 | `STREET` | CHAR | 60 |  | Street |
| 44 | `STREET2` | CHAR | 40 |  | Street 2 |
| 45 | `STREET3` | CHAR | 40 |  | Street 3 |
| 46 | `AUTOPAY` | CHAR | 1 |  | Apply for autopay |
| 47 | `AUTOPAY_HANDLE` | CHAR | 1 |  | Autopay handled |
| 48 | `AUTOPAYCANC` | CHAR | 1 |  | Autopay cancellation status |
| 49 | `ACCTHOLDERID1` | CHAR | 60 |  | Autopay account holder 1 ID |
| 50 | `ACCTHOLDERID2` | CHAR | 60 |  | Autopay account holder 2 ID |
| 51 | `ACCTHOLDERID1TYP` | CHAR | 6 |  | Autopay account holder 1 ID type |
| 52 | `ACCTHOLDERID2TYP` | CHAR | 6 |  | Autopay account holder 2 ID Type |
| 53 | `ACCTHOLDERNAME1` | CHAR | 80 |  | Autopay account holder 1 name |
| 54 | `ACCTHOLDERNAME2` | CHAR | 80 |  | Autopay account holder 2 name |
| 55 | `WEBACCT` | CHAR | 1 |  | Open Webservice account |
| 56 | `HM` | CHAR | 1 |  | Home-move indicator |
| 57 | `HM_ACCT` | CHAR | 12 |  | Home move Contract Account |
| 58 | `PMO` | CHAR | 1 |  | Pending move-out |
| 59 | `PMO_ACCT` | CHAR | 12 |  | Pending move out Contract Account |
| 60 | `METER` | CHAR | 18 |  | Meter installed |
| 61 | `MR_TYPE` | CHAR | 1 |  | Type of Move-in reading |
| 62 | `ACCTFINALDATE` | DATS | 8 |  | Last account final date |
| 63 | `LMTRRDGDATE` | DATS | 8 |  | Last meter reading date |
| 64 | `NMTRRDGDATE` | DATS | 8 |  | Next meter reading date |
| 65 | `CUSTDATE` | DATS | 8 |  | Customer requested date |
| 66 | `FUTUREDATE` | DATS | 8 |  | Future Date |
| 67 | `ADDRPROOF` | CHAR | 1 |  | Status of address proof upload |
| 68 | `PHASE` | CHAR | 10 |  | 2 / 3 Phase meter |
| 69 | `AMP` | CHAR | 5 |  | Ampere |
| 70 | `TRADE_CLASS` | CHAR | 10 |  | Trade |
| 71 | `BIZAGREEMENT` | CHAR | 1 |  | Customer signature & compile for Business Agreement |
| 72 | `REMARK1` | CHAR | 100 |  | Remark |
| 73 | `REMARK2` | CHAR | 100 |  | Remark |
| 74 | `REMARK3` | CHAR | 100 |  | Remark |
| 75 | `REMARK4` | CHAR | 100 |  | Remark |
| 76 | `REMARK5` | CHAR | 100 |  | Remark |
| 77 | `LOGNUM` | CHAR | 100 |  | Log number |
| 78 | `LOGDATE` | DATS | 8 |  | The date for the log entry |
| 79 | `EBILL_SEL` | CHAR | 1 |  | Green Bill selected |
| 80 | `EBILL1` | CHAR | 60 |  | eBill email address 1 |
| 81 | `EBILL2` | CHAR | 60 |  | eBill email address 2 |
| 82 | `EBILL3` | CHAR | 60 |  | eBill email address 3 |
| 83 | `EBILL4` | CHAR | 60 |  | eBill email address 4 |
| 84 | `EBILL5` | CHAR | 60 |  | eBill email address 5 |
| 85 | `EBILL6` | CHAR | 60 |  | eBill email address 6 |
| 86 | `TC_ACCEPT` | CHAR | 1 |  | Accept Terms and Condition |
| 87 | `AREA` | CHAR | 9 |  | Area of Premise |
| 88 | `AREAUNIT` | CHAR | 10 |  | Unit of Area |
| 89 | `POSTAL` | CHAR | 3 |  | Postal address Indicator |
| 90 | `SEX` | CHAR | 1 |  | Sex of BP |
| 91 | `MI_DATE` | DATS | 8 |  | Move-in date |
| 92 | `ACCEPT_LAST_READ` | CHAR | 1 |  | Accept last reading ind. (Y/N) |
| 93 | `PREMISE_VALID` | CHAR | 1 |  | Premise validation |
| 94 | `BP_VALID` | CHAR | 1 |  | BP validation |
| 95 | `SUPPLYTYPE` | CHAR | 5 |  | Type of supply |
| 96 | `STATUS` | CHAR | 1 |  | Record Status (A, S, R, C, X) |
| 97 | `TYPE` | CHAR | 2 |  | Record Type (MI) |
| 98 | `SOURCE` | CHAR | 1 |  | Record Source (C - CLP Online) |
| 99 | `ASSIGNTO` | CHAR | 12 |  | User Name |
| 100 | `CREATIONDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 101 | `LASTCHANGEDATE` | DATS | 8 |  | Date of Last Change |
| 102 | `LASTCHANGEBY` | CHAR | 12 |  | Name of person who changed object |
| 103 | `CREATEBY` | CHAR | 12 |  | Name of Person Who create object |
| 104 | `DUEDATE` | DATS | 8 |  | Due Date |
| 105 | `TASK_STATUS` | CHAR | 1 |  | Status of the Task created in the Task Management |
| 106 | `ADDRPROOFUPLOAD` | CHAR | 1 |  | Status of address proof upload |
| 107 | `ADDRPROOFREQ` | CHAR | 1 |  | Address proof request status |
| 108 | `ADDRPROOFRECEIVE` | CHAR | 1 |  | Address proof received indicator |
| 109 | `MI_DOC` | CHAR | 12 |  | Consecutive number of move-in document |
| 110 | `TITLE` | CHAR | 5 |  | Customer Title |
| 111 | `TEMP_ACCT_FROM` | DATS | 8 |  | Temp supply from date |
| 112 | `TEMP_ACCT_TO` | DATS | 8 |  | Temp supply to date |
| 113 | `SMSNUM` | CHAR | 8 |  | SMS number |
| 114 | `SUBMIT_DATE` | DATS | 8 |  | Move-in submission date |
| 115 | `FMOREQ` | CHAR | 1 |  | Forced move-out request status |
| 116 | `PURECA` | CHAR | 1 |  | Pure CA |
| 117 | `FMOBY` | CHAR | 12 |  | Force MO Created By |
| 118 | `FMOON` | DATS | 8 |  | Force MO Created On |
| 119 | `ZZTRADE_CAT` | CHAR | 2 |  | Trade category |
| 120 | `ZZTRADE_CLASS` | CHAR | 10 |  | Trade |
| 121 | `ZZPREM_FUNC` | CHAR | 3 |  | Premise function |
| 122 | `RECIPIENT` | CHAR | 40 |  | C/O name |
| 123 | `READING` | DEC | 17 |  | Meter Reading |
| 124 | `TARIFF` | CHAR | 10 |  | Move-in Tariff |
| 125 | `REC_CHANNEL` | CHAR | 1 |  | Receive channel |
| 126 | `PREPOSTAL` | CHAR | 1 |  | Use Previous Postal Address |
| 127 | `SELFPOSTAL` | CHAR | 1 |  | Self Input Postal Address |
| 128 | `BP_ID_NUM_U` | CHAR | 60 |  | Updated BP ID No. |
| 129 | `BP_ID_TYPE_U` | CHAR | 6 |  | Update BP ID type |
| 130 | `BP_NAME_ENG1_U` | CHAR | 60 |  | Update BP Name 1 (English) |
| 131 | `BP_NAME_ENG2_U` | CHAR | 60 |  | Update BP Name 2 (English) |
| 132 | `MOBILENUM_U` | CHAR | 8 |  | Update Mobile num |
| 133 | `TARIFF_U` | CHAR | 10 |  | Tariff update |
| 134 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 135 | `CONSENT` | CHAR | 1 |  | Consent |
