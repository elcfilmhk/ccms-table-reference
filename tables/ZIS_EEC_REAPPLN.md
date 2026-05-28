# ZIS_EEC_REAPPLN
**Description:** RE Connection/ FiT Application
**Total Fields:** 91
**Key Fields:** MANDT, RE_APP_NO

## Programs Using This Table
- `zisbi0042`
- `ziscs0208`
- `ziscs0507`
- `ziscs0511`
- `ziscs0512`
- `ziscs0514`
- `ziscs0515`
- `ziscs0518`
- `ziscs0519`
- `ziscs0525`
- `ziscs0814`
- `ziscs0836`
- `ziscs0838`
- `ziscs0840`
- `ziscs1122`
- `ziscseec_comm_frmwrk_trigger==ft`
- `ziscseec_trig_fitaprv_process=ft`
- `zisdm0022`
- `zisdm0022_bulk`
- `zpc_rank_patch`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `AUFNR` | CHAR | 12 |  | Order Number |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `RE_APP_STATUS` | CHAR | 2 |  | RE Application Status |
| 6 | `VSTELLE` | CHAR | 10 |  | Premise |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `APP_TYPE` | CHAR | 2 |  | Application Type |
| 9 | `APP_REC_DATE` | DATS | 8 |  | Application received date |
| 10 | `FIT_RAT_VALI_PD` | CHAR | 2 |  | Validity Period(in Months) |
| 11 | `EXPIRY_DAT` | DATS | 8 |  | Expiry Date |
| 12 | `EXT_VAL_ALLOW` | CHAR | 2 |  | Validity Period(in Months) |
| 13 | `NO_OF_EXT` | CHAR | 2 |  | No of extensions allowed |
| 14 | `MAX_NO_OF_EXT` | CHAR | 2 |  | Max no of extensions allowed |
| 15 | `DOC_LINK` | CHAR | 250 |  | Document Repository Link |
| 16 | `TEC_DOC_LINK` | CHAR | 250 |  | Technical Document Link |
| 17 | `TOT_GEN_CAP` | QUAN | 9 |  | Total RE/FiT Capacity(kW) |
| 18 | `APP_CAP` | QUAN | 9 |  | Application RE/FiT Capacity(kW) |
| 19 | `EXP_COMP_DAT` | DATS | 8 |  | Expected Completion Date |
| 20 | `EXI_GRID_NO` | CHAR | 40 |  | Existing grid connection agreement no |
| 21 | `INST_LOC` | CHAR | 250 |  | Installation Location |
| 22 | `INST_TYP_ROOF` | CHAR | 1 |  | Room Installation Flag |
| 23 | `INST_TYP_POD` | CHAR | 1 |  | Podium Installation |
| 24 | `INST_TYP_LAND` | CHAR | 1 |  | Land Installation |
| 25 | `INST_TYP_OTH_FLAG` | CHAR | 1 |  | Others flag |
| 26 | `INST_TYP_OTH` | CHAR | 50 |  | Others Installation |
| 27 | `ACC_MNG_ID` | CHAR | 12 |  | Account Manager User Id |
| 28 | `RES_TEAM` | CHAR | 1 |  | Responsible Team |
| 29 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 30 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 31 | `EXT_EXP_DAT` | DATS | 8 |  | Extended Expiry Date |
| 32 | `ID_VERIF` | CHAR | 1 |  | ID Verified |
| 33 | `VERIFIED_ON` | DATS | 8 |  | Verified On |
| 34 | `PRE_MED` | CHAR | 1 |  | Preferred Medium |
| 35 | `PRE_COM_LANG` | CHAR | 2 |  | Communication Language |
| 36 | `CON_PERSON_SAL` | CHAR | 4 |  | Form-of-Address Key |
| 37 | `CON_PERSON_ENG_NAME` | CHAR | 60 |  | Contact Person English Name |
| 38 | `CON_PERSON_CHI_NAME` | CHAR | 60 |  | Contact Person Chinese Name |
| 39 | `CUST_CORR_ADD_NO` | CHAR | 10 |  | Address Number |
| 40 | `CUST_LAND_LINE_NO` | CHAR | 8 |  | LandLine number |
| 41 | `CON_ENG_NAME` | CHAR | 60 |  | Contractor's English Name |
| 42 | `CON_CHI_NAME` | CHAR | 60 |  | Contractor's Chinese Name |
| 43 | `CON_ENG_COMP` | CHAR | 60 |  | Contractor Company English Name |
| 44 | `CON_CHI_COMP` | CHAR | 60 |  | Contractor Company Chinese Name |
| 45 | `EMR_PER_NAME` | CHAR | 60 |  | Emergency Person Name |
| 46 | `EMR_CHI_NAME` | CHAR | 60 |  | Emergency Person Chinese Name |
| 47 | `PAY_OPTION` | CHAR | 2 |  | FiT Payment Option |
| 48 | `CNTPER_PHONE` | CHAR | 8 |  | Contact Information(Ph/Mob/Fax) |
| 49 | `CNTPER_MOBNO` | CHAR | 8 |  | Contact Information(Ph/Mob/Fax) |
| 50 | `CNTPER_FAXNO` | CHAR | 8 |  | Contact Information(Ph/Mob/Fax) |
| 51 | `CON_PHONE` | CHAR | 8 |  | Contact Information(Ph/Mob/Fax) |
| 52 | `EMR_PHONE` | CHAR | 8 |  | Contact Information(Ph/Mob/Fax) |
| 53 | `CNT_SMTP` | CHAR | 50 |  | Email Address |
| 54 | `CON_SMTP` | CHAR | 50 |  | Email Address |
| 55 | `EMR_SMTP` | CHAR | 50 |  | Email Address |
| 56 | `VERTRAG` | CHAR | 10 |  | Contract |
| 57 | `ACT_COMP_DATE` | DATS | 8 |  | Actual Completion Date |
| 58 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 59 | `ID_TYPE` | CHAR | 6 |  | ID Type for ID to be received from front end |
| 60 | `ID_NUM` | CHAR | 60 |  | Identification Number |
| 61 | `CANC_REASON` | CHAR | 2 |  | RE Application Cancellation Reason |
| 62 | `CANC_REASON_TEXT` | CHAR | 100 |  | RE Application Cancellation Reason Text |
| 63 | `GCA_REF_NUM` | CHAR | 50 |  | GCA Ref# for New Connection |
| 64 | `GCA_SIGN_DATE` | DATS | 8 |  | GCA Signed Date |
| 65 | `CUST_MAIN_SWTCH_RAT` | DEC | 5 |  | Existing Customer Main Switch Rating |
| 66 | `ORIG_APP_CAP` | QUAN | 9 |  | Original Application RE Capacity(kW) |
| 67 | `ORIG_ELEC_OUTPUT` | CHAR | 1 |  | Original RE Electricity Output |
| 68 | `ZB_FIT_START_DATE` | DATS | 8 |  | ZBULK- Meter Installation Date(FiT Start) |
| 69 | `TECH_DOC_MISS_PREV` | CHAR | 1 |  | Technical Document missed previously |
| 70 | `CAP_CHANGE_COUNT` | INT1 | 3 |  | Number of times Application Capacity has been changed |
| 71 | `CAP_CHANGE_DATE` | DATS | 8 |  | Application Capacity changed date |
| 72 | `ZB_EXEC_DATE` | DATS | 8 |  | ZBULK Execution Date |
| 73 | `EXI_VOL_LEVL` | CHAR | 2 |  | Existing Voltage Level |
| 74 | `BUILD_TYPE` | CHAR | 2 |  | Building Type |
| 75 | `BUILD_DESC` | CHAR | 100 |  | Building Description |
| 76 | `REC` | CHAR | 1 |  | Interested in REC |
| 77 | `PREV_COMP_APP` | CHAR | 12 |  | Previous Completed |
| 78 | `EXT_TERM_DATE` | DATS | 8 |  | Extended Termination Date |
| 79 | `PREV_OUT_APP` | CHAR | 12 |  | Previous Outstanding |
| 80 | `SCHEMATIC` | CHAR | 1 |  | Schematic |
| 81 | `LAYOUT_PLAN` | CHAR | 1 |  | Layout Plan |
| 82 | `CONSENT_BUILD_VILL` | CHAR | 1 |  | Consent form for High-rise buildings and Village house |
| 83 | `VIDEO_ACCESS` | CHAR | 1 |  | Video Access for free |
| 84 | `REMARKS` | CHAR | 255 |  | Remarks |
| 85 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 86 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 87 | `ERZET` | TIMS | 6 |  | Entry time |
| 88 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 89 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 90 | `AEZET` | TIMS | 6 |  | Time last change was made |
| 91 | `DOC_SP_LINK` | CHAR | 250 |  | Doc SharePoint folder |
