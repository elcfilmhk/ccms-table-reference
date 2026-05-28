# ZISCS_522_EXTR
**Description:** Table for ZCS522 Data Extactor with Customer Info
**Total Fields:** 141
**Key Fields:** MANDT, RE_APP_NO, RE_SYS_LOC, RE_SOURCE

## Programs Using This Table
- `ziscs0518`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RE_APP_NO` | CHAR | 12 | 🔑 | Notification No |
| 3 | `RE_SYS_LOC` | CHAR | 10 | 🔑 | RE System Location |
| 4 | `RE_SOURCE` | CHAR | 30 | 🔑 | RE Source |
| 5 | `REGCUSNAME` | CHAR | 80 |  | Registered Customer Name |
| 6 | `SUP_ADDRESS` | CHAR | 255 |  | Supply Premise |
| 7 | `COR_ADDRESS` | CHAR | 255 |  | Correspondence Address |
| 8 | `CNT_SMTP` | CHAR | 50 |  | Contact Persion Email |
| 9 | `CON_SMTP` | CHAR | 50 |  | Contractor Email |
| 10 | `APP_CRT_DT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `APP_REC_DATE` | DATS | 8 |  | Application received date |
| 12 | `PRELIM_REV_DATE` | DATS | 8 |  | Prelim. Sup. Doc. Reviewed Date |
| 13 | `PRELIM_INPROG_DATE` | DATS | 8 |  | Prelim. Sup. Doc. In Progress Date |
| 14 | `TECH_DOC_MISS_PREV` | CHAR | 1 |  | Technical Document missed previously |
| 15 | `ONLIN_APP` | CHAR | 1 |  | Online Application |
| 16 | `APP_TYPE` | CHAR | 30 |  | Application Type |
| 17 | `GRID` | CHAR | 1 |  | With Grid-Connection |
| 18 | `PREV_COM_APP` | CHAR | 12 |  | Previous Completed |
| 19 | `CAPCHANGE` | CHAR | 30 |  | Capacity Change |
| 20 | `PART_CAP_APR` | CHAR | 1 |  | Partial Capacity Approved |
| 21 | `TXT30` | CHAR | 30 |  | Object status |
| 22 | `RE_APP_STATUS` | CHAR | 100 |  | RE Application Status |
| 23 | `G_LOCATION_TYPE` | CHAR | 50 |  | Location Type |
| 24 | `EXI_GRID_NO` | CHAR | 40 |  | Existing grid connection agreement no |
| 25 | `GCA_REF_NUM` | CHAR | 50 |  | GCA Ref# for New Connection |
| 26 | `GCA_SIGN_DATE` | DATS | 8 |  | GCA Signed Date |
| 27 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 28 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 29 | `DISTRICT` | CHAR | 40 |  | District |
| 30 | `ACC_MNG_ID` | CHAR | 80 |  | Acc.Manager Name |
| 31 | `INST_REC` | CHAR | 1 |  | Interested in REC |
| 32 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 33 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 34 | `ORIG_ELEC_OUTPUT` | CHAR | 60 |  | Original RE Electricity Output |
| 35 | `ELEC_OUT` | CHAR | 60 |  | Current RE Electricity Output |
| 36 | `BUILD_TYPE` | CHAR | 100 |  | Building Type |
| 37 | `BUILD_DESC` | CHAR | 100 |  | Building Description |
| 38 | `CUST_MAIN_SWTCH_RAT` | DEC | 5 |  | Existing Customer Main Switch Rating |
| 39 | `EXI_VOL_LEVL` | CHAR | 30 |  | Existing Voltage Level |
| 40 | `SPEBENE` | CHAR | 30 |  | Current Voltage Level |
| 41 | `ZZAPPRLOAD` | DEC | 9 |  | Approved Loading |
| 42 | `ORIG_APP_CAP` | QUAN | 9 |  | Original Application RE Capacity(kW) |
| 43 | `MAX_CAP_ALLOWED` | QUAN | 9 |  | Maximum Allowable Capacity(kW) |
| 44 | `PROV_APP_FIT_CAP2` | QUAN | 9 |  | Application RE/FiT Capacity at Location(kW) |
| 45 | `FIT_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 46 | `PROV_APP_FIT_CAP` | QUAN | 9 |  | Gen. Capacity under this App at Loc.(kW) |
| 47 | `PROV_FIT_TOT_CAP` | QUAN | 9 |  | Total RE/FiT Capacity at Location(kW) |
| 48 | `CAP_CHANGE_COUNT` | INT1 | 3 |  | Capacity Change count |
| 49 | `CAP_CHANGE_DATE` | DATS | 8 |  | Last Capacity change Date |
| 50 | `DISPCHANGE` | CHAR | 10 |  | Distribution of Gen. Cap under this Appl |
| 51 | `ORD_CRT_DT` | DATS | 8 |  | Service order creation Date |
| 52 | `INWC_DT` | DATS | 8 |  | Insufficient Network Capacity Date |
| 53 | `NASF_DT` | DATS | 8 |  | Network Assessment Failed Date |
| 54 | `NAPT_DT` | DATS | 8 |  | Pending for technical info. Date |
| 55 | `RNWA_DT` | DATS | 8 |  | Resume Network Assessment Date |
| 56 | `NRRE_DT` | DATS | 8 |  | Netw Reinforcement Required Dt. |
| 57 | `NRPC_DT` | DATS | 8 |  | Reinf. Pend. Cust Reply dt |
| 58 | `REINF_REM_DATE` | DATS | 8 |  | Reinforcement Reminder Letter Sent Date |
| 59 | `PCDP_DT` | DATS | 8 |  | Pend. Cust. Agree with Det. Prop. Date |
| 60 | `PPPC_DT` | DATS | 8 |  | Pending P&D Project Scheme Date |
| 61 | `NRFP_DT` | DATS | 8 |  | Reinforcement Finalise Proposal Date |
| 62 | `NRPI_DT` | DATS | 8 |  | Reinforcement Issued Project Date |
| 63 | `COND_DT` | DATS | 8 |  | Reinf. Condition letter issue date |
| 64 | `NRLR_DT` | DATS | 8 |  | Reinf. Cond. letter &/ or depos. Received dt. |
| 65 | `LOAD_NUM` | CHAR | 12 |  | Change load no |
| 66 | `SCHEME_NO` | CHAR | 40 |  | Project Scheme No. |
| 67 | `LEAD_TIME` | CHAR | 3 |  | Estimated reinforcement lead time |
| 68 | `NRCO_DT` | DATS | 8 |  | Netw Reinforcement Completed Dt. |
| 69 | `NRCA_DT` | DATS | 8 |  | Netw Reinforcement Cancelled Dt. |
| 70 | `NASP_DT` | DATS | 8 |  | Netw Assessment Passed Date |
| 71 | `SO_ACTIVITY` | CHAR | 1 |  | Multiple SO activity |
| 72 | `CDATE` | DATS | 8 |  | Acknowledgement Letter Sent Date |
| 73 | `WRKDAY_3` | CHAR | 12 |  | Wkdays btw Appln Rec Dt & SO creation dt |
| 74 | `WRKDAY_4` | CHAR | 12 |  | Wkdays btw SO creation Dt & NASP Dt |
| 75 | `WRKDAY_5` | CHAR | 12 |  | Wkdays btw NASP Dt & Ack letter sent Dt |
| 76 | `G_ACTUAL_DAYS` | CHAR | 12 |  | Workdays btwn Appln. Rec. & Ackn. Letter |
| 77 | `SAOP_DT` | DATS | 8 |  | OP Report Received Date |
| 78 | `PFOP_DT` | DATS | 8 |  | Pending for Cust. Information-OP report |
| 79 | `OPSC_DT` | DATS | 8 |  | OP Submission Completed Date |
| 80 | `WRKDAY_6` | CHAR | 12 |  | Wkdays btw Ack let sent Dt & 1st SAOP Dt |
| 81 | `WRKDAY_7` | CHAR | 12 |  | Wkdays btw 1st NASP Date & 1st SAOP Date |
| 82 | `WRKDAY_8` | CHAR | 12 |  | Wkdays btw 1st SAOP Date & 1st PFOP Date |
| 83 | `WRKDAY_9` | CHAR | 12 |  | Working days in OP stage (cust. mixed) |
| 84 | `WRKDAY_10` | CHAR | 12 |  | Working days in OP stage (CLP) |
| 85 | `WRKDAY_11` | CHAR | 12 |  | Working days in OP stage (Only Customer) |
| 86 | `WRKDAY_12` | CHAR | 12 |  | Wkdays btw OPSC and 1st SATC Date |
| 87 | `SATC_DT` | DATS | 8 |  | TC Report Received Date |
| 88 | `PFTC_DT` | DATS | 8 |  | Pending for Customer Info-T&C report |
| 89 | `WRKDAY_13` | CHAR | 12 |  | Wkdays btw 1st SATC Dt and 1st PFTC Dt |
| 90 | `WRKDAY_14` | CHAR | 12 |  | Wkdays in TC stage (customer mixed) |
| 91 | `WRKDAY_15` | CHAR | 12 |  | Working Days in TC stage (CLP) |
| 92 | `WRKDAY_16` | CHAR | 12 |  | Working Days in TC Stage (Only Customer) |
| 93 | `TECHDOCSUB` | DATS | 8 |  | Technical Doc. Sub. Completion Date |
| 94 | `WRKDAY_17` | CHAR | 12 |  | Working Days between TDSC to 1st DMAP |
| 95 | `WRKDAY_18` | CHAR | 12 |  | Wkdays btw 1st DMAP to WCOM/1st SITF |
| 96 | `WRKDAY_19` | CHAR | 12 |  | Wkdays btw TDSC to WCOM/1st SITF |
| 97 | `WCOM_DT` | DATS | 8 |  | Service Order Completed Date |
| 98 | `SITF_OR_TREF_DT` | DATS | 8 |  | Site Test Failed Date |
| 99 | `ONSITE` | DATS | 8 |  | On-site Test Witness Date |
| 100 | `ONSTECH` | CHAR | 255 |  | Workdays for On-site and Technical Doc. |
| 101 | `EXPIRY_DAT` | DATS | 8 |  | Expiry Date |
| 102 | `EXT_EXP_DAT` | DATS | 8 |  | Extended Expiry Date |
| 103 | `NO_OF_EXT` | CHAR | 2 |  | No of extensions allowed |
| 104 | `GERAET` | CHAR | 18 |  | Meter Number |
| 105 | `METER_TYPE` | CHAR | 60 |  | Meter Type |
| 106 | `COM_NAME` | CHAR | 255 |  | Company Name English/Chinese |
| 107 | `COMM_START_DATE` | DATS | 8 |  | Meter Installation Date |
| 108 | `ZB_EXEC_DATE` | DATS | 8 |  | ZBULK Activity Execution Date |
| 109 | `WKDYS_BT_1` | CHAR | 12 |  | Workdays b/w ZBULK Exe & Meter Instln |
| 110 | `COM_DATE` | DATS | 8 |  | Completion Letter Sent Date |
| 111 | `WKDYS_BT_2` | CHAR | 12 |  | Workdays b/w Comp Ltr Date and ZBULK |
| 112 | `WORKING` | CHAR | 12 |  | Workdays b/w Comp Ltr Date & FiTCommDate |
| 113 | `AUFNR` | CHAR | 12 |  | Service Order |
| 114 | `REGION` | CHAR | 10 |  | Region |
| 115 | `INGPR` | CHAR | 3 |  | Service order planner group |
| 116 | `ILART` | CHAR | 3 |  | Service order PM Activity Type |
| 117 | `VAPLZ` | CHAR | 8 |  | Service order work centre |
| 118 | `NA_USERID` | CHAR | 12 |  | NAEIC User id |
| 119 | `SA_USERID` | CHAR | 12 |  | SAIEC User id |
| 120 | `CANC_REASON` | CHAR | 100 |  | Application Cancellation Reason |
| 121 | `CANC_REASON_TEXT` | CHAR | 100 |  | Application Cancellation Remark |
| 122 | `NASF_REASON1_CODE` | CHAR | 1 |  | NASFReason1-Over Approved Loading |
| 123 | `NASF_REASON2_CODE` | CHAR | 1 |  | NASFReason2-Over Tx 30% Limit |
| 124 | `NASF_REASON3_CODE` | CHAR | 1 |  | NASFReason3-Voltage Rise Issue |
| 125 | `NASF_REASON4_CODE` | CHAR | 1 |  | NASFReason4-No Network Coverage |
| 126 | `NASF_REASON5_CODE` | CHAR | 1 |  | NASFReason5-3-Phase RE application at 1- |
| 127 | `NASF_REASON6_CODE` | CHAR | 1 |  | NASFReason6-Duplicate application |
| 128 | `NASF_REASON7_CODE` | CHAR | 1 |  | NASFReason7-More than 10kW for 1-Phase R |
| 129 | `NASF_REASON8_CODE` | CHAR | 1 |  | NASFReason8-Incorrect RE Installation Lo |
| 130 | `NASF_REASON9_CODE` | CHAR | 1 |  | NASFReason9-Capacity Exceeded, Network n |
| 131 | `NASF_REASON10_CODE` | CHAR | 1 |  | NASFReasonOther-Other (Please Specify) |
| 132 | `NASF_REMARK` | CHAR | 128 |  | NASF Remark |
| 133 | `CHANGE_FIT` | CHAR | 100 |  | Customer Change FiT Application |
| 134 | `CHANGE_INST` | CHAR | 100 |  | Customer Installation Modification |
| 135 | `SCOPE_WORK` | CHAR | 100 |  | CLP Work Scope |
| 136 | `LEAD_TIME2_SO_DET` | CHAR | 3 |  | Estimated Lead time (in month) |
| 137 | `VRKME` | UNIT | 3 |  | Sales Unit |
| 138 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 139 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 140 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 141 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
