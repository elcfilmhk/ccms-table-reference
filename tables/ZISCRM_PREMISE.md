# ZISCRM_PREMISE
**Description:** Premise information for CRM general enquiry factsheet
**Total Fields:** 36
**Key Fields:** _none_

## Programs Using This Table
- `ziscrm_prem_genenq_fs=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PREMISE` | CHAR | 10 |  | Premise |
| 2 | `LOADING` | DEC | 9 |  | Approved Loading |
| 3 | `SUP_MOVEIN_FLAG` | CHAR | 1 |  | Suppress Move-in flag |
| 4 | `VACANT_DAYS` | NUMC | 4 |  | Number of Days |
| 5 | `VACANT_CONSUMPTION` | DEC | 16 |  | Entry value (installed value) for a device |
| 6 | `DISCONNECT_STAT` | CHAR | 60 |  | Explanatory Short Text |
| 7 | `NXT_METER_READ_DATE` | DATS | 8 |  | Scheduled meter reading date |
| 8 | `DEVICE_NUM` | CHAR | 18 |  | Serial Number |
| 9 | `DEVICE_CATEGORY` | CHAR | 18 |  | Material Number |
| 10 | `REGISTER_FACTOR` | DEC | 12 |  | Register factor |
| 11 | `METER_SIZE` | CHAR | 18 |  | Size/dimension |
| 12 | `FLOOR` | DEC | 9 |  | Floor Area in Square Meters |
| 13 | `PREMISE_TYPE` | CHAR | 8 |  | Type of premise |
| 14 | `RATE_CAT` | CHAR | 40 |  | Text for Rate Category |
| 15 | `PREMISE_NOTE` | CHAR | 132 |  | Text line |
| 16 | `PRE_METER_SWITCH_IND` | CHAR | 1 |  | Pre-meter switch |
| 17 | `METER_ROOM_IND` | CHAR | 1 |  | Meter Room Indicator |
| 18 | `FUNCLOC_TEXT` | CHAR | 132 |  | Text line |
| 19 | `MOVEIN_DAT` | DATS | 8 |  | Move-In Date |
| 20 | `MOVEOUT_DAT` | DATS | 8 |  | Move-Out Date |
| 21 | `CABLE_REMV_IND` | CHAR | 1 |  | Cable Removal Indicator |
| 22 | `INITIAL_DEPOSIT` | INT4 | 10 |  | Initial Deposit |
| 23 | `DEVICE_INFO` | CHAR | 30 |  | Device category description |
| 24 | `NEXT_BILL_DATE` | DATS | 8 |  | Scheduled Billing Date |
| 25 | `DEVICE_LOC_ADD` | CHAR | 30 |  | Addition to device location |
| 26 | `VOLTAGE_LEVEL_TEXT` | CHAR | 30 |  | Voltage Level |
| 27 | `ZZSUPDUNNINGRC` | CHAR | 1 |  | Suppress Dunning Reconnection flag |
| 28 | `CT_START_DATE` | DATS | 8 |  | Move-In Date |
| 29 | `CT_END_DATE` | DATS | 8 |  | Move-Out Date |
| 30 | `ZUI_BPNNUM` | CHAR | 10 |  | Business Partner Number |
| 31 | `ZUI_BPNAME` | CHAR | 80 |  | Char 80 |
| 32 | `ZUI_BA` | CHAR | 12 |  | Contract Account Number |
| 33 | `ZZSSR` | CHAR | 1 |  | SSR Premise |
| 34 | `ZZEVMAINCONSENT` | CHAR | 1 |  | EV With rising mains consent |
| 35 | `ZZEVEHSS` | CHAR | 1 |  | EV EHSS |
| 36 | `ZZEVUSAGE` | CHAR | 1 |  | EV Usage |
