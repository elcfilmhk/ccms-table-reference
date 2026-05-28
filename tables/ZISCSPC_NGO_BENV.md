# ZISCSPC_NGO_BENV
**Description:** Generated Table for View
**Total Fields:** 43
**Key Fields:** HQCODE, BHCODE, UCODE, CNTPERSON, NGOUROLE, NGOEML, NGOCNT, BPNUMBER, APPLN_REF, PROG_ID, VKONT, VKONT_MASK, BEN_TITLE, BEN_NAME, BEN_CNAME, LANGU_CORR, BEN_ADDR, BEN_TYPE, BEN_TEXT, BEN_CA_NAME, HK_ID, HK_ID_MASK, BEN_HM_PH, BEN_MOBL, BEN_EMAIL, NGO_CODE, NGO_UID, SUPDOC_TYPE, SUPDOC_NO, APPLN_DATE, DATA_SRC, APPLN_STAT, DELETION_IND, BEN_CONTACT_PERSON, BEN_CONTACT_PERSON_NUM, REL_WITH_APPL_PERSON, REL_WITH_APPL_ELECT_ACC, RESP_PERSON_NAME, RESP_PERSON_NUM, REL_WITH_APPL_RESP_PERSON, REL_WITH_APPL_BANK, REMARK, PROG

## Programs Using This Table
- `ziscspc_ngo_search_branch=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `HQCODE` | CHAR | 5 | 🔑 | Head Quarter Code |
| 2 | `BHCODE` | CHAR | 8 | 🔑 | Branch Code |
| 3 | `UCODE` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 4 | `CNTPERSON` | CHAR | 15 | 🔑 | Name of NGO User |
| 5 | `NGOUROLE` | NUMC | 2 | 🔑 | NGO User Role |
| 6 | `NGOEML` | CHAR | 50 | 🔑 | NGO Email |
| 7 | `NGOCNT` | NUMC | 8 | 🔑 | NGO Contact |
| 8 | `BPNUMBER` | CHAR | 10 | 🔑 | Business Partner Number |
| 9 | `APPLN_REF` | CHAR | 10 | 🔑 | Application Reference Number |
| 10 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 11 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 12 | `VKONT_MASK` | CHAR | 12 | 🔑 | Contract Account Number |
| 13 | `BEN_TITLE` | CHAR | 4 | 🔑 | Form-of-Address Key |
| 14 | `BEN_NAME` | CHAR | 40 | 🔑 | Beneficiary Name |
| 15 | `BEN_CNAME` | CHAR | 40 | 🔑 | Beneficiary Chinese name |
| 16 | `LANGU_CORR` | LANG | 1 | 🔑 | Business Partner: Correspondence Language |
| 17 | `BEN_ADDR` | CHAR | 10 | 🔑 | Address Number |
| 18 | `BEN_TYPE` | CHAR | 2 | 🔑 | Beneficiary ID |
| 19 | `BEN_TEXT` | CHAR | 12 | 🔑 | Beneficiary Type |
| 20 | `BEN_CA_NAME` | CHAR | 35 | 🔑 | Contract Account Name |
| 21 | `HK_ID` | CHAR | 60 | 🔑 | Identification Number |
| 22 | `HK_ID_MASK` | CHAR | 60 | 🔑 | Identification Number |
| 23 | `BEN_HM_PH` | NUMC | 8 | 🔑 | Beneficiary Home Telephone Number |
| 24 | `BEN_MOBL` | NUMC | 8 | 🔑 | Beneficiary Mobile Number |
| 25 | `BEN_EMAIL` | CHAR | 30 | 🔑 | Beneficiary e-mail |
| 26 | `NGO_CODE` | CHAR | 8 | 🔑 | Branch Code |
| 27 | `NGO_UID` | CHAR | 12 | 🔑 | NGO User ID in Application table |
| 28 | `SUPDOC_TYPE` | CHAR | 5 | 🔑 | SDU ID |
| 29 | `SUPDOC_NO` | CHAR | 20 | 🔑 | Supporting doc. no. |
| 30 | `APPLN_DATE` | DATS | 8 | 🔑 | Application Date |
| 31 | `DATA_SRC` | CHAR | 5 | 🔑 | Data Source |
| 32 | `APPLN_STAT` | CHAR | 12 | 🔑 | Beneficiary Status Code |
| 33 | `DELETION_IND` | CHAR | 1 | 🔑 | Single-Character Flag |
| 34 | `BEN_CONTACT_PERSON` | CHAR | 40 | 🔑 | Beneficiary Contact Person |
| 35 | `BEN_CONTACT_PERSON_NUM` | NUMC | 8 | 🔑 | Beneficiary Contact Person Number |
| 36 | `REL_WITH_APPL_PERSON` | CHAR | 2 | 🔑 | Relationship With Applicant(Contact Person) |
| 37 | `REL_WITH_APPL_ELECT_ACC` | CHAR | 2 | 🔑 | Relationship With Applicant(Contract Account) |
| 38 | `RESP_PERSON_NAME` | CHAR | 40 | 🔑 | Responsible Person Name |
| 39 | `RESP_PERSON_NUM` | NUMC | 8 | 🔑 | Beneficiary Contact Person Number |
| 40 | `REL_WITH_APPL_RESP_PERSON` | CHAR | 2 | 🔑 | Relationship with Applicant(Responsible Person) |
| 41 | `REL_WITH_APPL_BANK` | CHAR | 100 | 🔑 | Payment remark |
| 42 | `REMARK` | CHAR | 255 | 🔑 | Remarks |
| 43 | `PROG` | CHAR | 3 | 🔑 | Programme type |
