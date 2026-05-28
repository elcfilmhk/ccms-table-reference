# ZISDH_MESSAGE_DWN
**Description:** Meter task message download
**Total Fields:** 51
**Key Fields:** _none_

## Programs Using This Table
- `z_meter_task_fetch============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TASK` | STRU | 0 |  | Fields for Meter Task Download |
| 2 | `CALLID` | CHAR | 40 |  | CallID |
| 3 | `PCID` | CHAR | 1 |  | PC ID |
| 4 | `MAIN_MRU` | CHAR | 8 |  | Meter Reading Unit |
| 5 | `EARLY_START` | CHAR | 19 |  | Date/Time format relevant for Service Opt. Server |
| 6 | `ROUTE_TYPE` | CHAR | 3 |  | Route Type |
| 7 | `TASK_TYPE` | CHAR | 20 |  | Task Type |
| 8 | `DIFFICULTY_LEVEL` | INT1 | 3 |  | Difficulty level of route |
| 9 | `DURATION` | NUMC | 4 |  | Count parameters |
| 10 | `ROUTE_MSG` | CHAR | 80 |  | Route Message |
| 11 | `CRITICAL_DATE` | CHAR | 19 |  | Date/Time format relevant for Service Opt. Server |
| 12 | `OC` | CHAR | 3 |  | Operation Centre |
| 13 | `PACK_ID` | CHAR | 20 |  | Pack ID |
| 14 | `MR_GROUP` | CHAR | 2 |  | Meter Reading Group |
| 15 | `CLP_ZONE` | CHAR | 3 |  | CLP Zone |
| 16 | `MIMO_REMARKS` | CHAR | 80 |  | Move-In Move-Out Remarks |
| 17 | `CUSTOMER` | STRU | 0 |  | Customer Details for Message Download |
| 18 | `ACCOUNT_NUMBER` | CHAR | 20 |  | Account Number |
| 19 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 20 | `INST_MRU` | CHAR | 8 |  | Meter reading unit |
| 21 | `MR_REASON` | CHAR | 2 |  | Meter reading reason |
| 22 | `NAME` | CHAR | 40 |  | Customer Name |
| 23 | `ADDRESS` | CHAR | 80 |  | Customer Address |
| 24 | `RATE_CATEGORY` | CHAR | 2 |  | Rate Category |
| 25 | `WO_NUMBER` | CHAR | 12 |  | Service order or notification |
| 26 | `MAINT_ACT_TYPE` | CHAR | 3 |  | Maintenance activity type |
| 27 | `ORDER_INST` | CHAR | 80 |  | Order Instruction |
| 28 | `PORTION` | CHAR | 8 |  | Portion |
| 29 | `METER` | STRU | 0 |  | Meter details for message download |
| 30 | `METER_NUMBER` | CHAR | 18 |  | Serial Number |
| 31 | `METER_STATUS` | CHAR | 1 |  | Meter Status |
| 32 | `SCHED_MR_DATE` | CHAR | 19 |  | Date/Time format relevant for Service Opt. Server |
| 33 | `PREVIOUS_READER` | CHAR | 30 |  | Text (30 Characters) |
| 34 | `SERVICE_TYPE` | CHAR | 2 |  | Division |
| 35 | `METER_TYPE` | CHAR | 1 |  | Meter Type (Value - 'T' or 'M') |
| 36 | `SEQUENCE_NO` | NUMC | 8 |  | Route Sequence No. |
| 37 | `MR_NOTE` | CHAR | 80 |  | Meter Reading Note |
| 38 | `CONS_EST` | NUMC | 2 |  | Consecutive Estimates |
| 39 | `SEAL_NO` | CHAR | 25 |  | Technical identification number |
| 40 | `MR_METHOD` | CHAR | 20 |  | Meter Reading Method |
| 41 | `TECH_OBJ_TYPE` | CHAR | 10 |  | Type of Technical Object |
| 42 | `TOU_INT_ID` | CHAR | 18 |  | TOU Internal ID |
| 43 | `TOU_METER_MODEL` | CHAR | 20 |  | Manufacturer model number |
| 44 | `TOU_RATE_ID` | CHAR | 30 |  | Characteristic Value |
| 45 | `ACTION` | TTYP | 0 |  | Action details for message download |
| 46 | `REGISTER` | TTYP | 0 |  | Register reading for message download |
| 47 | `SKILLS` | STRU | 0 |  | Skill details for Message Download |
| 48 | `COMPETANT_PERSON` | CHAR | 1 |  | Boolean format for SOS |
| 49 | `CUSTOMER_CONTACT` | CHAR | 1 |  | Boolean format for SOS |
| 50 | `METER_RESEAL` | CHAR | 1 |  | Boolean format for SOS |
| 51 | `DURATION_ACTUAL` | NUMC | 4 |  | Count parameters |
