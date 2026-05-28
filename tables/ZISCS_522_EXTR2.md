# ZISCS_522_EXTR2
**Description:** Table for ZCS522 Data Extactor without Customer Info
**Total Fields:** 137
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
| 5 | `SUP_ADDRESS` | CHAR | 255 |  | Supply Premise |
| 6 | `APP_CRT_DT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `APP_REC_DATE` | DATS | 8 |  | Application received date |
| 8 | `PRELIM_REV_DATE` | DATS | 8 |  | Prelim. Sup. Doc. Reviewed Date |
| 9 | `PRELIM_INPROG_DATE` | DATS | 8 |  | Prelim. Sup. Doc. In Progress Date |
| 10 | `TECH_DOC_MISS_PREV` | CHAR | 1 |  | Technical Document missed previously |
| 11 | `ONLIN_APP` | CHAR | 1 |  | Online Application |
| 12 | `APP_TYPE` | CHAR | 30 |  | Application Type |
| 13 | `GRID` | CHAR | 1 |  | With Grid-Connection |
| 14 | `PREV_COM_APP` | CHAR | 12 |  | Previous Completed |
| 15 | `CAPCHANGE` | CHAR | 30 |  | Capacity Change |
| 16 | `PART_CAP_APR` | CHAR | 1 |  | Partial Capacity Approved |
| 17 | `TXT30` | CHAR | 30 |  | Object status |
| 18 | `RE_APP_STATUS` | CHAR | 100 |  | RE Application Status |
| 19 | `G_LOCATION_TYPE` | CHAR | 50 |  | Location Type |
| 20 | `EXI_GRID_NO` | CHAR | 40 |  | Existing grid connection agreement no |
| 21 | `GCA_REF_NUM` | CHAR | 50 |  | GCA Ref# for New Connection |
| 22 | `GCA_SIGN_DATE` | DATS | 8 |  | GCA Signed Date |
| 23 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 24 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 25 | `DISTRICT` | CHAR | 40 |  | District |
| 26 | `ACC_MNG_ID` | CHAR | 80 |  | Acc.Manager Name |
| 27 | `INST_REC` | CHAR | 1 |  | Interested in REC |
| 28 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 29 | `RE_SYS_NAM` | CHAR | 100 |  | RE System Location Name |
| 30 | `ORIG_ELEC_OUTPUT` | CHAR | 60 |  | Original RE Electricity Output |
| 31 | `ELEC_OUT` | CHAR | 60 |  | Current RE Electricity Output |
| 32 | `BUILD_TYPE` | CHAR | 100 |  | Building Type |
| 33 | `BUILD_DESC` | CHAR | 100 |  | Building Description |
| 34 | `CUST_MAIN_SWTCH_RAT` | DEC | 5 |  | Existing Customer Main Switch Rating |
| 35 | `EXI_VOL_LEVL` | CHAR | 30 |  | Existing Voltage Level |
| 36 | `SPEBENE` | CHAR | 30 |  | Current Voltage Level |
| 37 | `ZZAPPRLOAD` | DEC | 9 |  | Approved Loading |
| 38 | `ORIG_APP_CAP` | QUAN | 9 |  | Original Application RE Capacity(kW) |
| 39 | `MAX_CAP_ALLOWED` | QUAN | 9 |  | Maximum Allowable Capacity(kW) |
| 40 | `PROV_APP_FIT_CAP2` | QUAN | 9 |  | Application RE/FiT Capacity at Location(kW) |
| 41 | `FIT_CAPACITY` | QUAN | 9 |  | RE/FiT Capacity(kW) |
| 42 | `PROV_APP_FIT_CAP` | QUAN | 9 |  | Gen. Capacity under this App at Loc.(kW) |
| 43 | `PROV_FIT_TOT_CAP` | QUAN | 9 |  | Total RE/FiT Capacity at Location(kW) |
| 44 | `CAP_CHANGE_COUNT` | INT1 | 3 |  | Capacity Change count |
| 45 | `CAP_CHANGE_DATE` | DATS | 8 |  | Last Capacity change Date |
| 46 | `DISPCHANGE` | CHAR | 10 |  | Distribution of Gen. Cap under this Appl |
| 47 | `ORD_CRT_DT` | DATS | 8 |  | Service order creation Date |
| 48 | `INWC_DT` | DATS | 8 |  | Insufficient Network Capacity Date |
| 49 | `NASF_DT` | DATS | 8 |  | Network Assessment Failed Date |
| 50 | `NAPT_DT` | DATS | 8 |  | Pending for technical info. Date |
| 51 | `RNWA_DT` | DATS | 8 |  | Resume Network Assessment Date |
| 52 | `NRRE_DT` | DATS | 8 |  | Netw Reinforcement Required Dt. |
| 53 | `NRPC_DT` | DATS | 8 |  | Reinf. Pend. Cust Reply dt |
| 54 | `REINF_REM_DATE` | DATS | 8 |  | Reinforcement Reminder Letter Sent Date |
| 55 | `PCDP_DT` | DATS | 8 |  | Pend. Cust. Agree with Det. Prop. Date |
| 56 | `PPPC_DT` | DATS | 8 |  | Pending P&D Project Scheme Date |
| 57 | `NRFP_DT` | DATS | 8 |  | Reinforcement Finalise Proposal Date |
| 58 | `NRPI_DT` | DATS | 8 |  | Reinforcement Issued Project Date |
| 59 | `COND_DT` | DATS | 8 |  | Reinf. Condition letter issue date |
| 60 | `NRLR_DT` | DATS | 8 |  | Reinf. Cond. letter &/ or depos. Received dt. |
| 61 | `LOAD_NUM` | CHAR | 12 |  | Change load no |
| 62 | `SCHEME_NO` | CHAR | 40 |  | Project Scheme No. |
| 63 | `LEAD_TIME` | CHAR | 3 |  | Estimated reinforcement lead time |
| 64 | `NRCO_DT` | DATS | 8 |  | Netw Reinforcement Completed Dt. |
| 65 | `NRCA_DT` | DATS | 8 |  | Netw Reinforcement Cancelled Dt. |
| 66 | `NASP_DT` | DATS | 8 |  | Netw Assessment Passed Date |
| 67 | `SO_ACTIVITY` | CHAR | 1 |  | Multiple SO activity |
| 68 | `CDATE` | DATS | 8 |  | Acknowledgement Letter Sent Date |
| 69 | `WRKDAY_3` | CHAR | 12 |  | Wkdays btw Appln Rec Dt & SO creation dt |
| 70 | `WRKDAY_4` | CHAR | 12 |  | Wkdays btw SO creation Dt & NASP Dt |
| 71 | `WRKDAY_5` | CHAR | 12 |  | Wkdays btw NASP Dt & Ack letter sent Dt |
| 72 | `G_ACTUAL_DAYS` | CHAR | 12 |  | Workdays btwn Appln. Rec. & Ackn. Letter |
| 73 | `SAOP_DT` | DATS | 8 |  | OP Report Received Date |
| 74 | `PFOP_DT` | DATS | 8 |  | Pending for Cust. Information-OP report |
| 75 | `OPSC_DT` | DATS | 8 |  | OP Submission Completed Date |
| 76 | `WRKDAY_6` | CHAR | 12 |  | Wkdays btw Ack let sent Dt & 1st SAOP Dt |
| 77 | `WRKDAY_7` | CHAR | 12 |  | Wkdays btw 1st NASP Date & 1st SAOP Date |
| 78 | `WRKDAY_8` | CHAR | 12 |  | Wkdays btw 1st SAOP Date & 1st PFOP Date |
| 79 | `WRKDAY_9` | CHAR | 12 |  | Working days in OP stage (cust. mixed) |
| 80 | `WRKDAY_10` | CHAR | 12 |  | Working days in OP stage (CLP) |
| 81 | `WRKDAY_11` | CHAR | 12 |  | Working days in OP stage (Only Customer) |
| 82 | `WRKDAY_12` | CHAR | 12 |  | Wkdays btw OPSC and 1st SATC Date |
| 83 | `SATC_DT` | DATS | 8 |  | TC Report Received Date |
| 84 | `PFTC_DT` | DATS | 8 |  | Pending for Customer Info-T&C report |
| 85 | `WRKDAY_13` | CHAR | 12 |  | Wkdays btw 1st SATC Dt and 1st PFTC Dt |
| 86 | `WRKDAY_14` | CHAR | 12 |  | Wkdays in TC stage (customer mixed) |
| 87 | `WRKDAY_15` | CHAR | 12 |  | Working Days in TC stage (CLP) |
| 88 | `WRKDAY_16` | CHAR | 12 |  | Working Days in TC Stage (Only Customer) |
| 89 | `TECHDOCSUB` | DATS | 8 |  | Technical Doc. Sub. Completion Date |
| 90 | `WRKDAY_17` | CHAR | 12 |  | Working Days between TDSC to 1st DMAP |
| 91 | `WRKDAY_18` | CHAR | 12 |  | Wkdays btw 1st DMAP to WCOM/1st SITF |
| 92 | `WRKDAY_19` | CHAR | 12 |  | Wkdays btw TDSC to WCOM/1st SITF |
| 93 | `WCOM_DT` | DATS | 8 |  | Service Order Completed Date |
| 94 | `SITF_OR_TREF_DT` | DATS | 8 |  | Site Test Failed Date |
| 95 | `ONSITE` | DATS | 8 |  | On-site Test Witness Date |
| 96 | `ONSTECH` | CHAR | 255 |  | Workdays for On-site and Technical Doc. |
| 97 | `EXPIRY_DAT` | DATS | 8 |  | Expiry Date |
| 98 | `EXT_EXP_DAT` | DATS | 8 |  | Extended Expiry Date |
| 99 | `NO_OF_EXT` | CHAR | 2 |  | No of extensions allowed |
| 100 | `GERAET` | CHAR | 18 |  | Meter Number |
| 101 | `METER_TYPE` | CHAR | 60 |  | Meter Type |
| 102 | `COM_NAME` | CHAR | 255 |  | Company Name English/Chinese |
| 103 | `COMM_START_DATE` | DATS | 8 |  | Meter Installation Date |
| 104 | `ZB_EXEC_DATE` | DATS | 8 |  | ZBULK Activity Execution Date |
| 105 | `WKDYS_BT_1` | CHAR | 12 |  | Workdays b/w ZBULK Exe & Meter Instln |
| 106 | `COM_DATE` | DATS | 8 |  | Completion Letter Sent Date |
| 107 | `WKDYS_BT_2` | CHAR | 12 |  | Workdays b/w Comp Ltr Date and ZBULK |
| 108 | `WORKING` | CHAR | 12 |  | Workdays b/w Comp Ltr Date & FiTCommDate |
| 109 | `AUFNR` | CHAR | 12 |  | Service Order |
| 110 | `REGION` | CHAR | 10 |  | Region |
| 111 | `INGPR` | CHAR | 3 |  | Service order planner group |
| 112 | `ILART` | CHAR | 3 |  | Service order PM Activity Type |
| 113 | `VAPLZ` | CHAR | 8 |  | Service order work centre |
| 114 | `NA_USERID` | CHAR | 12 |  | NAEIC User id |
| 115 | `SA_USERID` | CHAR | 12 |  | SAIEC User id |
| 116 | `CANC_REASON` | CHAR | 100 |  | Application Cancellation Reason |
| 117 | `CANC_REASON_TEXT` | CHAR | 100 |  | Application Cancellation Remark |
| 118 | `NASF_REASON1_CODE` | CHAR | 1 |  | NASFReason1-Over Approved Loading |
| 119 | `NASF_REASON2_CODE` | CHAR | 1 |  | NASFReason2-Over Tx 30% Limit |
| 120 | `NASF_REASON3_CODE` | CHAR | 1 |  | NASFReason3-Voltage Rise Issue |
| 121 | `NASF_REASON4_CODE` | CHAR | 1 |  | NASFReason4-No Network Coverage |
| 122 | `NASF_REASON5_CODE` | CHAR | 1 |  | NASFReason5-3-Phase RE application at 1- |
| 123 | `NASF_REASON6_CODE` | CHAR | 1 |  | NASFReason6-Duplicate application |
| 124 | `NASF_REASON7_CODE` | CHAR | 1 |  | NASFReason7-More than 10kW for 1-Phase R |
| 125 | `NASF_REASON8_CODE` | CHAR | 1 |  | NASFReason8-Incorrect RE Installation Lo |
| 126 | `NASF_REASON9_CODE` | CHAR | 1 |  | NASFReason9-Capacity Exceeded, Network n |
| 127 | `NASF_REASON10_CODE` | CHAR | 1 |  | NASFReasonOther-Other (Please Specify) |
| 128 | `NASF_REMARK` | CHAR | 128 |  | NASF Remark |
| 129 | `CHANGE_FIT` | CHAR | 100 |  | Customer Change FiT Application |
| 130 | `CHANGE_INST` | CHAR | 100 |  | Customer Installation Modification |
| 131 | `SCOPE_WORK` | CHAR | 100 |  | CLP Work Scope |
| 132 | `LEAD_TIME2_SO_DET` | CHAR | 3 |  | Estimated Lead time (in month) |
| 133 | `VRKME` | UNIT | 3 |  | Sales Unit |
| 134 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 135 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 136 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 137 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
