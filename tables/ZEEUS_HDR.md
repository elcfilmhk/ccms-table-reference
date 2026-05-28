# ZEEUS_HDR
**Description:** EEUS Application Header Table
**Total Fields:** 64
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0520`
- `ziscs0522`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `EEUS_APPLN` | CHAR | 10 |  | EEUS Application Number |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `STATUS` | CHAR | 2 |  | Application status |
| 5 | `CUST_TYPE` | CHAR | 1 |  | Customer Type |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `VERTRAG` | CHAR | 10 |  | Contract |
| 8 | `EEUS_CR_SRC` | CHAR | 2 |  | EEUS Creation Source |
| 9 | `PUR_FROM` | CHAR | 2 |  | Purchase From |
| 10 | `CON_PERSON` | CHAR | 60 |  | Name of Contact Person |
| 11 | `EDMS_LINK` | CHAR | 250 |  | EDMS Link |
| 12 | `PRE_INST_ASGNDAT` | DATS | 8 |  | Pre Installation Assigned Date |
| 13 | `PRE_INST_COMPDAT` | DATS | 8 |  | Pre Installation Completion Date |
| 14 | `PRE_INST_RESLT` | CHAR | 1 |  | Pre Installation Result |
| 15 | `PRE_CANT_BE_NO` | CHAR | 2 |  | Count of Cannot be Contacted |
| 16 | `PRE_INST_REM` | CHAR | 150 |  | Remarks |
| 17 | `PRE_DOWN_DATE` | DATS | 8 |  | Pre Installation Download Date |
| 18 | `POST_INST_ASGNDAT` | DATS | 8 |  | Post Installation Assigned Date |
| 19 | `POST_INST_COMPDAT` | DATS | 8 |  | Post Installation Completion Date |
| 20 | `POST_INST_RESLT` | CHAR | 1 |  | Post Installation Result |
| 21 | `POST_CANT_BE_NO` | CHAR | 2 |  | Count of Cannot be Contacted |
| 22 | `POST_INST_REM` | CHAR | 150 |  | Remarks |
| 23 | `POST_DOWN_DATE` | DATS | 8 |  | Post Installation Download Date |
| 24 | `DOWN_FILE_TYPE` | CHAR | 1 |  | Download File Type |
| 25 | `REQUESTOR` | CHAR | 12 |  | Requestor |
| 26 | `REQUEST_DAT` | DATS | 8 |  | Requested On Date |
| 27 | `FIRST_L_RSLT` | CHAR | 1 |  | EEUS First Level Result |
| 28 | `FIRST_L_DAT` | DATS | 8 |  | First Level Approval Date |
| 29 | `FIRST_L_APPRV` | CHAR | 12 |  | First Level Approver |
| 30 | `FIRST_L_REM` | CHAR | 150 |  | Remarks |
| 31 | `SCND_L_RSLT` | CHAR | 1 |  | EEUS Second Level Result |
| 32 | `SCND_L_DAT` | DATS | 8 |  | Second Level Approval Date |
| 33 | `SCND_L_APPRV` | CHAR | 12 |  | Second Level Approver |
| 34 | `SCND_L_REM` | CHAR | 150 |  | Remarks |
| 35 | `ONLINE_RSLT` | CHAR | 1 |  | EEUS Application Online Submission - Result |
| 36 | `ONLINE_RLS_DAT` | DATS | 8 |  | EEUS Application Online Submission - Release Date |
| 37 | `ONLINE_APPRV` | CHAR | 12 |  | EEUS Application Online Submission V Checked By |
| 38 | `ONL_APRV_REMARKS` | CHAR | 150 |  | Remarks |
| 39 | `FIN_ENDRS_RSLT` | CHAR | 1 |  | EEUS Finance Endorser |
| 40 | `FIN_ENDRS_DAT` | DATS | 8 |  | Finance Endorser date |
| 41 | `FIN_ENDRS_APPRV` | CHAR | 12 |  | Finance Endorser |
| 42 | `FIN_REM` | CHAR | 150 |  | Remarks |
| 43 | `APP_REVIEWED` | CHAR | 1 |  | Application Review |
| 44 | `APP_REVIEWED_DAT` | DATS | 8 |  | Application Review Date |
| 45 | `APP_REVIEWED_BY` | CHAR | 12 |  | Application Reviewed By |
| 46 | `POST_APP_REV` | CHAR | 1 |  | Application Review |
| 47 | `POST_APP_REV_DAT` | DATS | 8 |  | Application Review Date |
| 48 | `POST_APP_REV_BY` | CHAR | 12 |  | Application Reviewed By |
| 49 | `EXEM_SEC88` | CHAR | 1 |  | Institution Tax Exempt(section 88)Inland Revenue Ordinance |
| 50 | `PAY_METHOD` | CHAR | 2 |  | Payment Method |
| 51 | `EXTVENDOR` | CHAR | 40 |  | External Vendor for Post Installation |
| 52 | `BUS_NATURE` | CHAR | 4 |  | Customer Business Nature |
| 53 | `CONT_PHONE` | CHAR | 8 |  | Contact Information(Ph/Mob/Fax) |
| 54 | `CONT_EMAIL` | CHAR | 50 |  | Email Address |
| 55 | `PREF_CHANNEL` | CHAR | 1 |  | Preferred Channel for Communication |
| 56 | `PROJ_COMP_DAT` | DATS | 8 |  | Project Completion Date |
| 57 | `REV_DATE` | DATS | 8 |  | Reversal Date |
| 58 | `APP_COMP_DATE` | DATS | 8 |  | Completion Date |
| 59 | `ACC_MNG_ID` | CHAR | 12 |  | Account Manager User Id |
| 60 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 61 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 62 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 63 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 64 | `MODE` | CHAR | 1 |  | Mode Insert - I /Delete - D /Update -U |
