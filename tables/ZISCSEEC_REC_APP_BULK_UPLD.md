# ZISCSEEC_REC_APP_BULK_UPLD
**Description:** Structure for Application Bulk Upload
**Total Fields:** 77
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0514`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RE_APP_NO` | CHAR | 12 |  | Notification No |
| 2 | `APP_REC_DATE` | CHAR | 10 |  | Character Field Length = 10 |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `APP_TYPE` | CHAR | 2 |  | Application Type |
| 5 | `RES_TEAM` | CHAR | 1 |  | Responsible Team |
| 6 | `CON_PERSON_SAL` | CHAR | 4 |  | Form-of-Address Key |
| 7 | `CON_PERSON_ENG_NAME` | CHAR | 60 |  | Contact Person English Name |
| 8 | `CON_PERSON_CHI_NAME` | CHAR | 60 |  | Contact Person Chinese Name |
| 9 | `ID_VERIF` | CHAR | 1 |  | ID Verified |
| 10 | `VERIFIED_ON` | CHAR | 10 |  | Character Field Length = 10 |
| 11 | `PAY_OPTION` | CHAR | 2 |  | Version Number Component |
| 12 | `CONP_PHN_NUM` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 13 | `CONP_MOB_PHN` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 14 | `CONP_FAX_NO` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 15 | `CONP_EMAIL_ADD` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 16 | `PRE_MED` | CHAR | 1 |  | Preferred Medium |
| 17 | `PRE_COM_LANG` | CHAR | 2 |  | Communication Language |
| 18 | `INST_TYP` | CHAR | 10 |  | Character Field Length = 10 |
| 19 | `INST_LOC` | CHAR | 250 |  | Installation Location |
| 20 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 21 | `RE_SYS_NAM_CH` | CHAR | 100 |  | Description |
| 22 | `EXP_COMP_DAT` | CHAR | 10 |  | Character Field Length = 10 |
| 23 | `APP_CAP` | CHAR | 12 |  | Character Field of Length 12 |
| 24 | `TOT_GEN_CAP` | CHAR | 12 |  | Character Field of Length 12 |
| 25 | `RE_SOURCE` | CHAR | 2 |  | RE Source |
| 26 | `ELEC_OUTPUT` | CHAR | 1 |  | Electricity Output(in phase) |
| 27 | `EXI_GRID_NO` | CHAR | 40 |  | Existing grid connection agreement no |
| 28 | `CON_ENG_COMP` | CHAR | 60 |  | Contractor Company English Name |
| 29 | `CON_CHI_COMP` | CHAR | 60 |  | Contractor Company Chinese Name |
| 30 | `CON_ENG_NAME` | CHAR | 60 |  | Contractor's English Name |
| 31 | `CON_CHI_NAME` | CHAR | 60 |  | Contractor's Chinese Name |
| 32 | `CONT_PHN_NUM` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 33 | `CONT_EMAIL_ADD` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 34 | `EMR_PER_NAME` | CHAR | 60 |  | Emergency Person Name |
| 35 | `EMR_CHI_NAME` | CHAR | 60 |  | Emergency Person Chinese Name |
| 36 | `EMR_PHN_NUM` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 37 | `EMR_EMAIL_ADD` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 38 | `NSEIC_USR_ID` | CHAR | 12 |  | User Name in User Master Record |
| 39 | `NSEIC_NAME` | CHAR | 60 |  | Contractor's English Name |
| 40 | `NSEIC_PHN_NUM` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 41 | `NSEIC_EMAIL_ADD` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 42 | `ACC_MNG_ID` | CHAR | 12 |  | User Name in User Master Record |
| 43 | `PROV_FIT_RATE` | CHAR | 17 |  | 17-Char. Field |
| 44 | `ACK_LTR_DAT` | CHAR | 10 |  | Character Field Length = 10 |
| 45 | `NO_OF_EXT` | CHAR | 2 |  | No of extensions allowed |
| 46 | `EXT_EXP_DAT` | CHAR | 10 |  | Character Field Length = 10 |
| 47 | `SAEIC_USR_ID` | CHAR | 12 |  | User Name in User Master Record |
| 48 | `SAEIC_NAME` | CHAR | 60 |  | Contractor's English Name |
| 49 | `SAEIC_PHN_NUM` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 50 | `SAEIC_EMAIL_ADD` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 51 | `EDMS_LINK` | CHAR | 250 |  | EDMS Link (Operation Procedure) |
| 52 | `ARR_SITE_TEST_DT` | CHAR | 10 |  | Character Field Length = 10 |
| 53 | `RE_FIT_PPM_MTR_TYP` | CHAR | 1 |  | Meter Type |
| 54 | `RE_FIT_PPM_MTR_NM` | NUMC | 18 |  | Logical device number |
| 55 | `SMART_BI_DIR_MTR_TYP` | CHAR | 1 |  | Meter Type |
| 56 | `SMART_BI_DIR_MTR_NM` | NUMC | 18 |  | Logical device number |
| 57 | `PPM_BI_DIR_MTR_TYP` | CHAR | 1 |  | Meter Type |
| 58 | `PPM_BI_DIR_MTR_NM` | NUMC | 18 |  | Logical device number |
| 59 | `CLP_REV_BI_DIR_MTR_TYP` | CHAR | 1 |  | Meter Type |
| 60 | `CLP_REV_BI_DIR_MTR_NM` | NUMC | 18 |  | Logical device number |
| 61 | `APP_COMP_DT` | CHAR | 10 |  | Character Field Length = 10 |
| 62 | `FIT_RATE` | CHAR | 17 |  | 17-Char. Field |
| 63 | `NET_ASS_PASS` | CHAR | 10 |  | Character Field Length = 10 |
| 64 | `NET_REINFO_REQ` | CHAR | 10 |  | Character Field Length = 10 |
| 65 | `NET_ASS_FAIL` | CHAR | 10 |  | Character Field Length = 10 |
| 66 | `TERM_LTR_SND` | CHAR | 10 |  | Character Field Length = 10 |
| 67 | `CONT_INST_SUB_DT` | CHAR | 10 |  | Character Field Length = 10 |
| 68 | `SITE_PASS_MT_INS_DT` | CHAR | 10 |  | Character Field Length = 10 |
| 69 | `COMP_LTR_SND_DT` | CHAR | 10 |  | Character Field Length = 10 |
| 70 | `FIT_RAT_VALI_PD` | CHAR | 2 |  | Validity Period(in Months) |
| 71 | `EXPIRY_DAT` | CHAR | 10 |  | Character Field Length = 10 |
| 72 | `EXT_VAL_ALLOW` | CHAR | 2 |  | Validity Period(in Months) |
| 73 | `FIT_CAPACITY` | CHAR | 12 |  | Character Field of Length 12 |
| 74 | `VSTELLE` | CHAR | 10 |  | Premise |
| 75 | `RE_APP_STATUS` | CHAR | 2 |  | RE Application Status |
| 76 | `MSG` | CHAR | 200 |  | Text field length 200 |
| 77 | `FLAG` | CHAR | 1 |  | Single-Character Flag |
