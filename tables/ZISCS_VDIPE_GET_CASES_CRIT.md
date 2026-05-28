# ZISCS_VDIPE_GET_CASES_CRIT
**Description:** Search Criteria for FM Z_VDIP_ENQ_GET_CASES_WS
**Total Fields:** 33
**Key Fields:** _none_

## Programs Using This Table
- `z_vdip_enq_get_cases_ws=======ft`
- `zcl_z_vdip_enq_get_cas_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CASE_ID` | CHAR | 20 |  | CaseID (allow wildcards) |
| 2 | `COMP_NAME` | CHAR | 100 |  | Company Name of customer |
| 3 | `CASE_STR_ERG2` | CHAR | 40 |  | Street 3 |
| 4 | `CASE_STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 5 | `CASE_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 6 | `CASE_STREET` | CHAR | 60 |  | Street |
| 7 | `CASE_CITY2` | CHAR | 40 |  | District |
| 8 | `CASE_CITY1` | CHAR | 40 |  | City |
| 9 | `CASE_FULL_ADDR` | CHAR | 300 |  | All Address fields concatenated |
| 10 | `CASE_TYPE` | CHAR | 4 |  | 'I': Type I cases; "II": Type II cases; etc |
| 11 | `CASE_ACC_MGR_USER` | CHAR | 12 |  | Username of Account Manager |
| 12 | `CREATE_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 13 | `CASE_REP_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 14 | `INCD_VOLT_LV` | CHAR | 10 |  | Investigation Result: Voltage Level |
| 15 | `INCD_CAUSE_CODE` | TTYP | 0 |  | Table of ZZISCS_RANGES_STRING |
| 16 | `CASE_STATUS` | CHAR | 1 |  | VoltDipEnquiry case Status |
| 17 | `COMPLETE_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 18 | `COMPLETE_USER` | TTYP | 0 |  | Table of ZZISCS_RANGES_STRING |
| 19 | `CANCEL_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 20 | `CANCEL_USER` | TTYP | 0 |  | Table of ZZISCS_RANGES_STRING |
| 21 | `INCD_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 22 | `INCD_ID_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 23 | `INCD_ID_USER` | TTYP | 0 |  | Table of ZZISCS_RANGES_STRING |
| 24 | `LAST_SENT_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 25 | `SERV_PLED_DT` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
| 26 | `VKONT` | CHAR | 14 |  | filter by CA, allow wildcards. |
| 27 | `CUSTOMER_NAME` | CHAR | 100 |  | Customer Name |
| 28 | `CUST_TEL` | CHAR | 30 |  | First telephone no.: dialling code+number |
| 29 | `CUST_FAX` | CHAR | 30 |  | First fax no.: dialling code+number |
| 30 | `CUST_EMAIL` | CHAR | 200 |  | Customer Email Address |
| 31 | `CUST_SEARCH` | CHAR | 1 |  | 'Y': Customer address searchable; 'N': otherwise |
| 32 | `OVERDUE` | CHAR | 1 |  | Single-Character Flag |
| 33 | `WORKDATE_0` | TTYP | 0 |  | Table of ZZISCS_RANGES_DATETIME |
