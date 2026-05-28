# ZISCSPC_PC_BEN_REG_S
**Description:** BAPI structure for beneficiary registration-PC
**Total Fields:** 40
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0800`
- `ziscspc_pc_ben_view===========ft`
- `ziscspc_pc_reg_ben============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `BEN_TITLE` | CHAR | 4 |  | Form-of-Address Key |
| 4 | `BEN_NAME` | CHAR | 40 |  | Beneficiary Name |
| 5 | `BEN_CNAME` | CHAR | 40 |  | Beneficiary Chinese name |
| 6 | `LANGU_CORR` | LANG | 1 |  | Business Partner: Correspondence Language |
| 7 | `BEN_ID` | CHAR | 2 |  | Beneficiary ID |
| 8 | `HK_ID` | CHAR | 60 |  | Identification Number |
| 9 | `NGO_CODE` | CHAR | 8 |  | Branch Code |
| 10 | `NGO_UID` | CHAR | 12 |  | User Name in User Master Record |
| 11 | `SUPDOC_ID` | CHAR | 5 |  | SDU ID |
| 12 | `SUPDOC_NO` | CHAR | 20 |  | Supporting doc. no. |
| 13 | `BEN_HM_PH` | NUMC | 8 |  | Beneficiary Home Telephone Number |
| 14 | `BEN_MOBL` | NUMC | 8 |  | Beneficiary Mobile Number |
| 15 | `BEN_EMAIL` | CHAR | 30 |  | Beneficiary e-mail |
| 16 | `APPLN_DATE` | DATS | 8 |  | Application Date |
| 17 | `DATA_SRC` | CHAR | 5 |  | Data Source |
| 18 | `APPLN_STATUS_CODE` | CHAR | 12 |  | Beneficiary Status Code |
| 19 | `STREET_NUM1` | CHAR | 40 |  | Street 2 |
| 20 | `STREET_NUM2` | CHAR | 40 |  | Street 3 |
| 21 | `ROOM_NUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 22 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 23 | `STREET` | CHAR | 60 |  | Street |
| 24 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 25 | `DISTRICT` | CHAR | 40 |  | District |
| 26 | `POST_CODE1` | CHAR | 10 |  | City postal code |
| 27 | `CITY` | CHAR | 40 |  | City |
| 28 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 29 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 30 | `BEN_CONTACT_PERSON` | CHAR | 40 |  | Beneficiary Contact Person |
| 31 | `BEN_CONTACT_PERSON_NUM` | NUMC | 8 |  | Beneficiary Contact Person Number |
| 32 | `REL_WITH_APPL_PERSON` | CHAR | 2 |  | Relationship With Applicant(Contact Person) |
| 33 | `REL_WITH_APPL_ELECT_ACC` | CHAR | 2 |  | Relationship With Applicant(Contract Account) |
| 34 | `RESP_PERSON_NAME` | CHAR | 40 |  | Responsible Person Name |
| 35 | `RESP_PERSON_NUM` | CHAR | 8 |  | Responsible Person Number |
| 36 | `REL_WITH_APPL_RESP_PERSON` | CHAR | 2 |  | Relationship with Applicant(Responsible Person) |
| 37 | `REL_WITH_APPL_BANK` | CHAR | 100 |  | Payment remark |
| 38 | `REMARK` | CHAR | 255 |  | Remarks |
| 39 | `UNIT` | CHAR | 10 |  | House number supplement |
| 40 | `MESSAGE` | CHAR | 255 |  | Comment |
