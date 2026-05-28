# ZISCS_EEC_EAAPP
**Description:** Energy Audit Application
**Total Fields:** 73
**Key Fields:** MANDT, EA_APP_NO

## Programs Using This Table
- `z_iscseec_po_details==========ft`
- `z_iscseec_requisition_delete==ft`
- `ziscs0526`
- `ziscs0723`
- `ziscs0725`
- `ziscs1122`
- `ziscseec_comm_frmwrk_eeus_ea==ft`
- `zpc_rank_patch`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EA_APP_NO` | CHAR | 12 | 🔑 | Energy Audit Application |
| 3 | `PRIM_VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `EA_APP_STATUS` | CHAR | 2 |  | Energy Audit Application Status |
| 5 | `DEF_ACC_MGR` | CHAR | 12 |  | Default Account Manager |
| 6 | `REF_ACC_MGR` | CHAR | 12 |  | Referred by Account Manager |
| 7 | `CANC_DAT` | DATS | 8 |  | Cancel date |
| 8 | `CANC_BY` | CHAR | 12 |  | Cancelled by |
| 9 | `CANC_RSN` | CHAR | 2 |  | Cancellation Reason |
| 10 | `CANC_REM` | CHAR | 60 |  | Cancellation Remarks |
| 11 | `DOC_LINK` | CHAR | 250 |  | Document Repository Link |
| 12 | `ORDER_HANDL_PARTY` | CHAR | 2 |  | Order Handling Party |
| 13 | `AUD_COORDINATOR` | CHAR | 60 |  | Energy Audit Coordinator Name |
| 14 | `AUDCORD_PHONE_NO` | CHAR | 8 |  | Energy Audit Coordinator Phone No |
| 15 | `AUDCORD_EMAILADD` | CHAR | 50 |  | Energy Audit Coordinator Email Address |
| 16 | `EA_ASSOCIATE` | CHAR | 60 |  | Energy Audit Associate Name |
| 17 | `ASSOC_PHONE_NO` | CHAR | 8 |  | Energy Audit Associate Phone No |
| 18 | `ASSOC_EMAILADD` | CHAR | 50 |  | Energy Audit Associate Email Address |
| 19 | `BANFN` | CHAR | 14 |  | Purchase Requisition Number |
| 20 | `BNFPO` | NUMC | 5 |  | Item number of purchase requisition |
| 21 | `EBELN` | CHAR | 10 |  | Purchasing Document Number |
| 22 | `PO_ISSUEDATE` | DATS | 8 |  | PO Issue Date |
| 23 | `PO_RECDATE` | DATS | 8 |  | PO Received Date |
| 24 | `VISIT_DAT` | DATS | 8 |  | Visit Date |
| 25 | `LAG_DATE` | DEC | 6 |  | Lag in Days |
| 26 | `RES_SITE_VISIT` | CHAR | 2 |  | Reason for late visit |
| 27 | `SUPP_INFO_REC_DAT` | DATS | 8 |  | Supp. Info Received Date |
| 28 | `CLPP_REP_SUB_DAT` | DATS | 8 |  | Report Submission Date (CLPP) |
| 29 | `CLNT_REP_SUB_DAT` | DATS | 8 |  | Report Submission Date (Client) |
| 30 | `CEAC_REC_DAT` | DATS | 8 |  | CEAC Received Date |
| 31 | `CEAC_VERIF_DAT` | DATS | 8 |  | CEAC Verified Date |
| 32 | `GR_DAT_NINETYSEVEN` | DATS | 8 |  | GR Date(97%) |
| 33 | `GR_AMNT_NINETYSEVEN` | CURR | 13 |  | GR Amount (97%) |
| 34 | `SURVEY_DAT` | DATS | 8 |  | Survey Form Sent Date |
| 35 | `SURVEY_RET_DAT` | DATS | 8 |  | Survey Form Returned Date |
| 36 | `GR_DAT_THREE` | DATS | 8 |  | GR Date(3%) |
| 37 | `GR_AMNT_THREE` | CURR | 13 |  | GR Amount (3%) |
| 38 | `CUST_TYPE` | CHAR | 2 |  | Customer Type |
| 39 | `CUST_BUS_NAT` | CHAR | 3 |  | Customer Business Nature |
| 40 | `CUST_BUS_NAT_OTH` | CHAR | 40 |  | Customer Business Nature Others |
| 41 | `PREMISE_TYP` | CHAR | 2 |  | Premise Type |
| 42 | `COMPANY_NAME` | CHAR | 100 |  | Company/Institution Name |
| 43 | `CON_PER_NAME` | CHAR | 60 |  | Contact Person Name |
| 44 | `CON_PER_DES` | CHAR | 100 |  | Contact Person Designation |
| 45 | `CON_PER_TEL` | CHAR | 8 |  | Contact Person Tel |
| 46 | `CON_PER_MOB` | CHAR | 8 |  | Contact Person Mobile |
| 47 | `CON_PER_FAX` | CHAR | 8 |  | Contact Person Fax |
| 48 | `CON_PER_EMAIL` | CHAR | 50 |  | Contact Person Email |
| 49 | `WORK_DAY_TIME_FROM` | TIMS | 6 |  | Monday to Friday working hours From |
| 50 | `WORK_DAY_TIME_TO` | TIMS | 6 |  | Monday to Friday working hours To |
| 51 | `SAT_OPEN` | CHAR | 1 |  | Saturday Open |
| 52 | `SAT_DAY_TIME_FROM` | TIMS | 6 |  | Saturday working hours From |
| 53 | `SAT_DAY_TIME_TO` | TIMS | 6 |  | Saturday working hours To |
| 54 | `SUN_OPEN` | CHAR | 1 |  | Sunday Open |
| 55 | `SUN_DAY_TIME_FROM` | TIMS | 6 |  | Sunday working hours From |
| 56 | `SUN_DAY_TIME_TO` | TIMS | 6 |  | Sunday working hours To |
| 57 | `NO_OF_EMP` | DEC | 6 |  | No of Employees |
| 58 | `FLOOR_AREA` | DEC | 10 |  | Floor Area |
| 59 | `EA_REFER_NO` | CHAR | 12 |  | Energy Audit Reference No |
| 60 | `BUIL_OP_YR` | CHAR | 4 |  | Building Operation Year |
| 61 | `MAJ_SIT_ADD` | CHAR | 50 |  | Major Site Address |
| 62 | `CLP_CON_NAME` | CHAR | 60 |  | CLP Contact Person Name |
| 63 | `CLP_CON_NO` | CHAR | 8 |  | CLP Contact Person Number |
| 64 | `CLP_CON_JOB` | CHAR | 100 |  | CLP Contact Person Job Title |
| 65 | `CUST_NAME` | CHAR | 80 |  | Customer name entered |
| 66 | `ELEC_ACC_NAME` | CHAR | 100 |  | Electricity Account Name |
| 67 | `FI_CO_CL_DAT` | DATS | 8 |  | First Contact Client Date |
| 68 | `PR_LOEKZ` | CHAR | 1 |  | Asset class marked for deletion |
| 69 | `COMP_DATE` | DATS | 8 |  | Completion date |
| 70 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 71 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 72 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 73 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
