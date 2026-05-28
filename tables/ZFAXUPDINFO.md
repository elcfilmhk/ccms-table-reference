# ZFAXUPDINFO
**Description:** Table for Change BP / Account Info through Fax and Letter
**Total Fields:** 91
**Key Fields:** MANDT, TXNNUM

## Programs Using This Table
- `ziscs0261`
- `ziscs0318`
- `ziscs0320`
- `ziscs0321`
- `ziscs0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `VSTELLE` | CHAR | 10 |  | Premise |
| 4 | `HAUS` | CHAR | 30 |  | Connection Object |
| 5 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 6 | `CONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 7 | `BP_NAME_ENG1` | CHAR | 80 |  | Business Partner Name (English) |
| 8 | `BP_NAME_ENG2` | CHAR | 80 |  | Business Partner Name (English) |
| 9 | `BP_NAME_CHI1` | CHAR | 60 |  | Business Partner Name (Chinese) |
| 10 | `BP_NAME_CHI2` | CHAR | 60 |  | Business Partner Name (Chinese) |
| 11 | `BP_ID_NUM` | CHAR | 60 |  | BP ID No. |
| 12 | `BP_ID_TYPE` | CHAR | 6 |  | BP ID Type |
| 13 | `ID_PROOF` | CHAR | 1 |  | Identity Proof Checked |
| 14 | `CONTACTNUM_O` | CHAR | 8 |  | Contact Phone No. |
| 15 | `EXT_O` | CHAR | 4 |  | Extension |
| 16 | `CONTACTNUM_N` | CHAR | 8 |  | Contact Phone No. |
| 17 | `EXT_N` | CHAR | 4 |  | Extension |
| 18 | `CONTACTNUM_OTHER` | CHAR | 8 |  | Contact Phone No. |
| 19 | `EXT_OTHER` | CHAR | 4 |  | Extension |
| 20 | `MOBILENUM` | CHAR | 8 |  | Mobile No. |
| 21 | `FAXNUM` | CHAR | 8 |  | Fax No. |
| 22 | `EMAIL1` | CHAR | 60 |  | Email Address |
| 23 | `EMAIL2` | CHAR | 60 |  | Email Address |
| 24 | `LANGU` | LANG | 1 |  | Language Key |
| 25 | `BMETHOD` | CHAR | 1 |  | Billing Method |
| 26 | `SUPPLYADDR` | CHAR | 100 |  | Supply Address |
| 27 | `POSTALADDR` | CHAR | 100 |  | Postal Address |
| 28 | `REMARK1` | CHAR | 100 |  | Remark |
| 29 | `REMARK2` | CHAR | 100 |  | Remark |
| 30 | `REMARK3` | CHAR | 100 |  | Remark |
| 31 | `REMARK4` | CHAR | 100 |  | Remark |
| 32 | `REMARK5` | CHAR | 100 |  | Remark |
| 33 | `LOGNUM` | CHAR | 100 |  | Log number |
| 34 | `LOGDATE` | DATS | 8 |  | The date for the log entry |
| 35 | `POSTAL` | CHAR | 3 |  | Postal address Indicator |
| 36 | `ASSIGNTO` | CHAR | 12 |  | User Name |
| 37 | `TASK_STATUS` | CHAR | 1 |  | Status of the Task created in the Task Management |
| 38 | `CREATIONDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 39 | `LASTCHANGEDATE` | DATS | 8 |  | Date of Last Change |
| 40 | `LASTCHANGEBY` | CHAR | 12 |  | Name of person who changed object |
| 41 | `CREATEBY` | CHAR | 12 |  | Created by |
| 42 | `DUEDATE` | DATS | 8 |  | Due Date |
| 43 | `SUBMIT_DATE` | DATS | 8 |  | Move-out submission date |
| 44 | `EBILL_CHANNEL` | CHAR | 5 |  | Ebill delivery channel |
| 45 | `EBILL` | CHAR | 1 |  | Green Bill selected |
| 46 | `EBILL1` | CHAR | 60 |  | eBill email address 1 |
| 47 | `EBILL2` | CHAR | 60 |  | eBill email address 2 |
| 48 | `EBILL3` | CHAR | 60 |  | eBill email address 3 |
| 49 | `EBILL4` | CHAR | 60 |  | eBill email address 4 |
| 50 | `EBILL5` | CHAR | 60 |  | eBill email address 5 |
| 51 | `EBILL6` | CHAR | 60 |  | eBill email address 6 |
| 52 | `STATUS` | CHAR | 1 |  | Record Status (A, S, R, C, X) |
| 53 | `BANKKEY` | CHAR | 15 |  | Bank Keys |
| 54 | `BANKACCT` | CHAR | 10 |  | Bank account number |
| 55 | `BANKBRANCHNO` | CHAR | 3 |  | Bank Branch No. |
| 56 | `ROOM` | CHAR | 10 |  | Room or Apartment Number |
| 57 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 58 | `RECIPIENT` | CHAR | 40 |  | C/O name |
| 59 | `STREET3` | CHAR | 40 |  | Street 3 |
| 60 | `STREET2` | CHAR | 40 |  | Street 2 |
| 61 | `STREET` | CHAR | 60 |  | Street |
| 62 | `HSE_NUM` | CHAR | 10 |  | House Number |
| 63 | `CITY` | CHAR | 40 |  | City |
| 64 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 65 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 66 | `DISTRICT` | CHAR | 40 |  | District |
| 67 | `AUTOPAY` | CHAR | 1 |  | Apply for autopay |
| 68 | `AUTOPAYCANC` | CHAR | 1 |  | Autopay cancellation status |
| 69 | `AUTOPAY_HANDLE` | CHAR | 1 |  | Autopay handled |
| 70 | `ACCTHOLDERID1` | CHAR | 60 |  | Autopay account holder 1 ID |
| 71 | `ACCTHOLDERID2` | CHAR | 60 |  | Autopay account holder 2 ID |
| 72 | `ACCTHOLDERID1TYP` | CHAR | 6 |  | Autopay account holder 1 ID type |
| 73 | `ACCTHOLDERID2TYP` | CHAR | 6 |  | Autopay account holder 2 ID Type |
| 74 | `ACCTHOLDERNAME1` | CHAR | 80 |  | Autopay account holder 1 name |
| 75 | `ACCTHOLDERNAME2` | CHAR | 80 |  | Autopay account holder 2 name |
| 76 | `WEBACCT` | CHAR | 1 |  | Open Webservice account |
| 77 | `RESETPASS` | CHAR | 1 |  | Reset password indicator |
| 78 | `DEACTIVATE` | CHAR | 1 |  | Deactivate webservice account indicator |
| 79 | `SMSNUM` | CHAR | 8 |  | SMS number |
| 80 | `TITLE` | CHAR | 5 |  | Customer Title |
| 81 | `REC_CHANNEL` | CHAR | 1 |  | Receive channel |
| 82 | `BP_ID_NUM_U` | CHAR | 60 |  | Updated BP ID No. |
| 83 | `BP_ID_TYPE_U` | CHAR | 6 |  | Update BP ID type |
| 84 | `BP_NAME_ENG1_U` | CHAR | 60 |  | Update BP Name 1 (English) |
| 85 | `BP_NAME_ENG2_U` | CHAR | 60 |  | Update BP Name 2 (English) |
| 86 | `BP_UPDATE` | CHAR | 1 |  | Flag to update BP info |
| 87 | `CONTACT_UPDATE` | CHAR | 1 |  | Flag to update Contact info |
| 88 | `BILLMET_UPDATE` | CHAR | 1 |  | Flag to update Billing method |
| 89 | `ADDR_UPDATE` | CHAR | 1 |  | Flag to update Address |
| 90 | `WEB_UPDATE` | CHAR | 1 |  | Flag to update Webservice account |
| 91 | `PA_DATE` | DATS | 8 |  | Postal Address Effective Date |
