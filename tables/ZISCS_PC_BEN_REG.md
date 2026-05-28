# ZISCS_PC_BEN_REG
**Description:** Beneficiary Registration under Power Connect
**Total Fields:** 42
**Key Fields:** MANDT, APPLN_REF, PROG_ID

## Programs Using This Table
- `z_iscspc_subsidy_lock_fail====ft`
- `z_iscspcchoicequotacalc=======ft`
- `zcl_ziscspc_ngo_sea_07_mpc`
- `zcl_zziscs_pc_ngo_sear_mpc`
- `ziscs0729`
- `ziscs0733`
- `ziscs0800`
- `ziscs0800_c`
- `ziscs0800_c1`
- `ziscs0802`
- `ziscs0805`
- `ziscs0815`
- `ziscs0815_01`
- `ziscs0817`
- `ziscs0828`
- `ziscs0829`
- `ziscs0833`
- `ziscs0837`
- `ziscs0839`
- `ziscs0855`
- `ziscs0856`
- `ziscs0857`
- `ziscs0858`
- `ziscs1120`
- `ziscspc_comm_frmwrk_trigger===ft`
- `ziscspc_ngo_prog_selection====ft`
- `zisfi0305`
- `zisfi0341`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `APPLN_REF` | CHAR | 10 | 🔑 | Application Reference Number |
| 3 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `BEN_TITLE` | CHAR | 4 |  | Form-of-Address Key |
| 6 | `BEN_NAME` | CHAR | 40 |  | Beneficiary Name |
| 7 | `BEN_CNAME` | CHAR | 40 |  | Beneficiary Chinese name |
| 8 | `LANGU_CORR` | LANG | 1 |  | Business Partner: Correspondence Language |
| 9 | `BEN_ADDR` | CHAR | 10 |  | Address Number |
| 10 | `BEN_TYPE` | CHAR | 2 |  | Beneficiary ID |
| 11 | `BEN_TEXT` | CHAR | 12 |  | Beneficiary Type |
| 12 | `BEN_CA_NAME` | CHAR | 35 |  | Contract Account Name |
| 13 | `HK_ID` | CHAR | 60 |  | Identification Number |
| 14 | `BEN_HM_PH` | NUMC | 8 |  | Beneficiary Home Telephone Number |
| 15 | `BEN_MOBL` | NUMC | 8 |  | Beneficiary Mobile Number |
| 16 | `BEN_EMAIL` | CHAR | 30 |  | Beneficiary e-mail |
| 17 | `NGO_CODE` | CHAR | 8 |  | Branch Code |
| 18 | `NGO_UID` | CHAR | 12 |  | NGO User ID in Application table |
| 19 | `SUPDOC_TYPE` | CHAR | 5 |  | SDU ID |
| 20 | `SUPDOC_NO` | CHAR | 20 |  | Supporting doc. no. |
| 21 | `BEN_CONTACT_PERSON` | CHAR | 40 |  | Beneficiary Contact Person |
| 22 | `BEN_CONTACT_PERSON_NUM` | NUMC | 8 |  | Beneficiary Contact Person Number |
| 23 | `REL_WITH_APPL_PERSON` | CHAR | 2 |  | Relationship With Applicant(Contact Person) |
| 24 | `REL_WITH_APPL_ELECT_ACC` | CHAR | 2 |  | Relationship With Applicant(Contract Account) |
| 25 | `RESP_PERSON_NAME` | CHAR | 40 |  | Responsible Person Name |
| 26 | `RESP_PERSON_NUM` | NUMC | 8 |  | Beneficiary Contact Person Number |
| 27 | `REL_WITH_APPL_RESP_PERSON` | CHAR | 2 |  | Relationship with Applicant(Responsible Person) |
| 28 | `REL_WITH_APPL_BANK` | CHAR | 100 |  | Payment remark |
| 29 | `REMARK` | CHAR | 255 |  | Remarks |
| 30 | `APPLN_DATE` | DATS | 8 |  | Application Date |
| 31 | `DATA_SRC` | CHAR | 5 |  | Data Source |
| 32 | `APPLN_STAT` | CHAR | 12 |  | Beneficiary Status Code |
| 33 | `DELETION_IND` | CHAR | 1 |  | Single-Character Flag |
| 34 | `MESSAGE` | CHAR | 255 |  | Comment |
| 35 | `BKVID` | CHAR | 4 |  | Bank details ID |
| 36 | `RANK` | NUMC | 8 |  | RANK |
| 37 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 38 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 39 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 40 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 41 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 42 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
