# ZISCSPC_SDU_BEN_REG_S
**Description:** BAPI structure for beneficiary registration for SDU
**Total Fields:** 49
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0800`
- `ziscspc_sdu_ben_view==========ft`
- `ziscspc_sdu_reg_ben===========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 2 | `BEN_TITLE` | CHAR | 4 |  | Form-of-Address Key |
| 3 | `BEN_NAME` | CHAR | 40 |  | Beneficiary Name |
| 4 | `BEN_CNAME` | CHAR | 40 |  | Beneficiary Chinese name |
| 5 | `LANGU_CORR` | LANG | 1 |  | Business Partner: Correspondence Language |
| 6 | `BEN_ID` | CHAR | 2 |  | Beneficiary ID |
| 7 | `HK_ID` | CHAR | 60 |  | Identification Number |
| 8 | `NGO_CODE` | CHAR | 8 |  | Branch Code |
| 9 | `NGO_UID` | CHAR | 12 |  | User Name in User Master Record |
| 10 | `SUPDOC_ID` | CHAR | 5 |  | SDU ID |
| 11 | `SUPDOC_NO` | CHAR | 20 |  | Supporting doc. no. |
| 12 | `BEN_HM_PH` | NUMC | 8 |  | Beneficiary Home Telephone Number |
| 13 | `BEN_MOBL` | NUMC | 8 |  | Beneficiary Mobile Number |
| 14 | `BEN_EMAIL` | CHAR | 30 |  | Beneficiary e-mail |
| 15 | `APPLN_DATE` | DATS | 8 |  | Application Date |
| 16 | `DATA_SRC` | CHAR | 5 |  | Data Source |
| 17 | `APPLN_STATUS_CODE` | CHAR | 12 |  | Beneficiary Status Code |
| 18 | `STREET_NUM1` | CHAR | 40 |  | Street 2 |
| 19 | `STREET_NUM2` | CHAR | 40 |  | Street 3 |
| 20 | `ROOM_NUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 21 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 22 | `STREET` | CHAR | 60 |  | Street |
| 23 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 24 | `DISTRICT` | CHAR | 40 |  | District |
| 25 | `POST_CODE1` | CHAR | 10 |  | City postal code |
| 26 | `CITY` | CHAR | 40 |  | City |
| 27 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 28 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 29 | `BANK_ID` | CHAR | 4 |  | Bank details ID |
| 30 | `BANK_CITY` | CHAR | 3 |  | Bank Country Key |
| 31 | `BANK_KEY` | CHAR | 15 |  | Bank Key |
| 32 | `BANK_ACCT_NUM` | CHAR | 18 |  | Bank Account Number |
| 33 | `BANK_CONTROL_KEY` | CHAR | 2 |  | Bank Control Key |
| 34 | `BANK_EXT_ID` | CHAR | 20 |  | Bank details ID in external system |
| 35 | `BANK_ACC_HOLDER_NAME` | CHAR | 60 |  | Account Holder Name |
| 36 | `BEN_CONTACT_PERSON` | CHAR | 40 |  | Beneficiary Contact Person |
| 37 | `BEN_CONTACT_PERSON_NUM` | NUMC | 8 |  | Beneficiary Contact Person Number |
| 38 | `REL_WITH_APPL_PERSON` | CHAR | 2 |  | Relationship With Applicant(Contact Person) |
| 39 | `REL_WITH_APPL_ELECT_ACC` | CHAR | 2 |  | Relationship With Applicant(Contract Account) |
| 40 | `RESP_PERSON_NAME` | CHAR | 40 |  | Responsible Person Name |
| 41 | `RESP_PERSON_NUM` | CHAR | 8 |  | Responsible Person Number |
| 42 | `REL_WITH_APPL_RESP_PERSON` | CHAR | 2 |  | Relationship with Applicant(Responsible Person) |
| 43 | `REL_WITH_APPL_BANK` | CHAR | 100 |  | Payment remark |
| 44 | `REMARK` | CHAR | 255 |  | Remarks |
| 45 | `UNIT` | CHAR | 10 |  | House number supplement |
| 46 | `BLOCK` | CHAR | 20 |  | Building (Number or Code) |
| 47 | `PHASE` | CHAR | 20 |  | Building (Number or Code) |
| 48 | `ESTATE` | CHAR | 20 |  | Building (Number or Code) |
| 49 | `MESSAGE` | CHAR | 255 |  | Comment |
