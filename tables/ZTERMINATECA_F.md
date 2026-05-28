# ZTERMINATECA_F
**Description:** Table of Move-out application through Fax and Letter
**Total Fields:** 82
**Key Fields:** MANDT, TXNNUM

## Programs Using This Table
- `ziscs0261`
- `ziscs0298`
- `ziscs0315`
- `ziscs0317`
- `ziscs0319`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXNNUM` | CHAR | 10 | 🔑 | CRM transaction no. |
| 3 | `VSTELLE` | CHAR | 10 |  | Premise |
| 4 | `HAUS` | CHAR | 30 |  | Connection Object |
| 5 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 6 | `ACCTCLASS` | CHAR | 4 |  | Acc. class |
| 7 | `CONTRACTACCT` | CHAR | 12 |  | Contract Account Number |
| 8 | `CONTRACT` | CHAR | 10 |  | Contract |
| 9 | `MOVEOUTDOC` | CHAR | 12 |  | Consecutive number of move-out document |
| 10 | `BP_NAME_ENG1` | CHAR | 80 |  | Business Partner Name (English) |
| 11 | `BP_NAME_ENG2` | CHAR | 80 |  | Business Partner Name (English) |
| 12 | `BP_NAME_CHI` | CHAR | 60 |  | Business Partner Name (Chinese) |
| 13 | `BP_ID_NUM` | CHAR | 60 |  | BP ID No. |
| 14 | `BP_ID_TYPE` | CHAR | 6 |  | BP ID Type |
| 15 | `ID_PROOF` | CHAR | 1 |  | Identity Proof Checked |
| 16 | `CONTACTNUM_O` | CHAR | 8 |  | Contact Phone No. |
| 17 | `EXT_O` | CHAR | 4 |  | Extension |
| 18 | `CONTACTNUM_N` | CHAR | 8 |  | Contact Phone No. |
| 19 | `EXT_N` | CHAR | 4 |  | Extension |
| 20 | `MOBILENUM` | CHAR | 8 |  | Mobile No. |
| 21 | `FAXNUM` | CHAR | 8 |  | Fax No. |
| 22 | `EMAIL1` | CHAR | 60 |  | Email Address |
| 23 | `EMAIL2` | CHAR | 60 |  | Email Address |
| 24 | `LANGU` | LANG | 1 |  | Language Key |
| 25 | `BMETHOD` | CHAR | 1 |  | Billing Method |
| 26 | `SUPPLYADDR` | CHAR | 100 |  | Supply Address |
| 27 | `POSTALADDR` | CHAR | 100 |  | Postal Address |
| 28 | `PMO` | CHAR | 1 |  | Pending move-out |
| 29 | `METER` | CHAR | 18 |  | Meter installed |
| 30 | `REMARK1` | CHAR | 100 |  | Remark |
| 31 | `REMARK2` | CHAR | 100 |  | Remark |
| 32 | `REMARK3` | CHAR | 100 |  | Remark |
| 33 | `REMARK4` | CHAR | 100 |  | Remark |
| 34 | `REMARK5` | CHAR | 100 |  | Remark |
| 35 | `LOGNUM` | CHAR | 100 |  | Log number |
| 36 | `LOGDATE` | DATS | 8 |  | The date for the log entry |
| 37 | `POSTAL` | CHAR | 3 |  | Postal address Indicator |
| 38 | `ASSIGNTO` | CHAR | 12 |  | User Name |
| 39 | `TASK_STATUS` | CHAR | 1 |  | Status of the Task created in the Task Management |
| 40 | `CREATIONDATE` | DATS | 8 |  | Date on Which Record Was Created |
| 41 | `LASTCHANGEDATE` | DATS | 8 |  | Date of Last Change |
| 42 | `LASTCHANGEBY` | CHAR | 12 |  | Name of person who changed object |
| 43 | `DUEDATE` | DATS | 8 |  | Due Date |
| 44 | `SUBMIT_DATE` | DATS | 8 |  | Info change submission date |
| 45 | `FORMDCHK` | CHAR | 1 |  | Form D Checked |
| 46 | `FORMLCHK` | CHAR | 1 |  | Form L Checkecd |
| 47 | `ZZREFUND_BY` | CHAR | 1 |  | Outgoing payment method |
| 48 | `BANK_ID` | CHAR | 4 |  | Existing Bank ID |
| 49 | `ZZEXT_ADD` | CHAR | 20 |  | External address number |
| 50 | `STATUS` | CHAR | 1 |  | Record Status (A, S, R, C, X) |
| 51 | `ZZEMAIL` | CHAR | 60 |  | Email |
| 52 | `ZZTEL` | CHAR | 8 |  | Tel. |
| 53 | `DISPATCH` | CHAR | 1 |  | The alert delivery method |
| 54 | `BANKKEY` | CHAR | 15 |  | Bank Keys |
| 55 | `BANKACCT` | CHAR | 18 |  | Bank account number |
| 56 | `ACCTHOLDER` | CHAR | 60 |  | Account Holder Name |
| 57 | `ROOM` | CHAR | 10 |  | Room or Apartment Number |
| 58 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 59 | `STREET` | CHAR | 60 |  | Street |
| 60 | `STREET2` | CHAR | 40 |  | Street 2 |
| 61 | `STREET3` | CHAR | 40 |  | Street 3 |
| 62 | `HSE_NUM` | CHAR | 10 |  | House Number |
| 63 | `CITY` | CHAR | 40 |  | City |
| 64 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 65 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 66 | `DISTRICT` | CHAR | 40 |  | District |
| 67 | `MO_DATE` | DATS | 8 |  | Move-out effective date |
| 68 | `TP_CA` | CHAR | 12 |  | TP_contract account |
| 69 | `CREATEBY` | CHAR | 12 |  | Created by |
| 70 | `RECIPIENT` | CHAR | 40 |  | C/O name |
| 71 | `ZZREFUND_STAFF` | CHAR | 60 |  | Name of the staff responsible to follow up the refund |
| 72 | `TP_NAME` | CHAR | 60 |  | BP name of the Target CA |
| 73 | `MR_TYPE` | CHAR | 1 |  | Type of MO reading |
| 74 | `LMTRRDGDATE` | DATS | 8 |  | Last meter reading date |
| 75 | `CUSTDATE` | DATS | 8 |  | Customer requested date |
| 76 | `FUTUREDATE` | DATS | 8 |  | Future Date |
| 77 | `READING` | DEC | 17 |  | Meter Reading |
| 78 | `BIZAGREEMENT` | CHAR | 1 |  | Customer signature & compile for Business Agreement |
| 79 | `ORGDEPRETRN` | CHAR | 1 |  | Original Deposit Receipt Returned |
| 80 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 81 | `REC_CHANNEL` | CHAR | 1 |  | Receive channel |
| 82 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
