# ZISBIPREXTRACT
**Description:** Print Document, Bill Type, & Tariff Type Mapping Table (New)
**Total Fields:** 61
**Key Fields:** MANDT, INV_DATE, OPBEL, CREATION_TIME, USER_NAME

## Programs Using This Table
- `zisbi0250`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INV_DATE` | DATS | 8 | 🔑 | Date |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `CREATION_TIME` | TIMS | 6 | 🔑 | System Time |
| 5 | `USER_NAME` | CHAR | 12 | 🔑 | User Name |
| 6 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 7 | `ZZBILLID` | CHAR | 2 |  | Bill ID |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 10 | `ZZRECIPIENT` | CHAR | 1 |  | Recipient |
| 11 | `ZZDELIVERY` | CHAR | 1 |  | Delivery Method |
| 12 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 13 | `MIN_CHARGE` | CHAR | 1 |  | Minimum Charge |
| 14 | `FULL_RATE` | CHAR | 1 |  | Full Charge |
| 15 | `WATER_HEATER` | CHAR | 1 |  | Water Heater |
| 16 | `AUTO_ADJ` | CHAR | 1 |  | Auto Adjusted |
| 17 | `CHILD` | CHAR | 1 |  | Child |
| 18 | `PRO_RATA` | CHAR | 1 |  | Pro rata |
| 19 | `LANGU` | LANG | 1 |  | Language Key |
| 20 | `FINAL_BILL` | CHAR | 1 |  | Final Bill |
| 21 | `FIRST_BILL` | CHAR | 1 |  | First Bill |
| 22 | `AMENDED` | CHAR | 1 |  | Amended |
| 23 | `BLOCK1` | CHAR | 1 |  | Block 1 |
| 24 | `BLOCK2` | CHAR | 1 |  | Block 2 |
| 25 | `BLOCK3` | CHAR | 1 |  | Block 3 |
| 26 | `KVA_BLOCK1` | CHAR | 1 |  | KVA Block 1 |
| 27 | `KVA_BLOCK2` | CHAR | 1 |  | KVA Block 2 |
| 28 | `KWH_BLOCK1` | CHAR | 1 |  | KWH Block 1 |
| 29 | `KWH_BLOCK2` | CHAR | 1 |  | KWH Block 2 |
| 30 | `HLFR_BLOCK1` | CHAR | 1 |  | HLFR Block 1 |
| 31 | `HLFR_BLOCK2` | CHAR | 1 |  | HLFR Block 2 |
| 32 | `KVA_MIN` | CHAR | 1 |  | KVA Min |
| 33 | `KVA_OFF_GT_ON` | CHAR | 1 |  | KVA Off > On |
| 34 | `KWH_OFF_GT_ON` | CHAR | 1 |  | KWH Off > On |
| 35 | `KWH_OFF_PEAK` | CHAR | 1 |  | KWH Off Peak |
| 36 | `KVA_WAIVE` | CHAR | 1 |  | KVA Waive |
| 37 | `KVA_SHORTFALL` | CHAR | 1 |  | KVA Shortfall |
| 38 | `DELIVERY_CHARGE` | CHAR | 1 |  | Delivery Charge |
| 39 | `FREE_UNIT` | CHAR | 1 |  | Free Unit |
| 40 | `INITIAL_CHARGE` | CHAR | 1 |  | Initial Charge |
| 41 | `HIGH_VOLT_RIDER` | CHAR | 1 |  | High Voltage Rider |
| 42 | `INCLUSIVE_UNIT` | CHAR | 1 |  | Inclusive Unit |
| 43 | `LP_BILLING` | CHAR | 1 |  | Load Profile Billing |
| 44 | `CB_BILLING` | CHAR | 1 |  | Complex Billing |
| 45 | `MONTH_BILL_ACT` | CHAR | 1 |  | Monthly Opt-In Bill (Actual) |
| 46 | `MONTH_BILL_EST` | CHAR | 1 |  | Monthly Opt-In Bill (Estimate) |
| 47 | `AMI_CUST_GRP` | CHAR | 8 |  | Current DSM Group for CA |
| 48 | `AMI_MTR_CONNECTED` | CHAR | 1 |  | AMI meter conencted |
| 49 | `PD_WITH_TOU` | CHAR | 1 |  | Indicator for printdoc contains TOU line item |
| 50 | `PD_WITH_PTR` | CHAR | 1 |  | Indicator for printdoc contains PTR line item |
| 51 | `OUTSORTED` | CHAR | 1 |  | Print Document is Outsorted |
| 52 | `HARDCOPY` | CHAR | 1 |  | Hardcopy Bill |
| 53 | `GREEN_BILL` | CHAR | 1 |  | Green Bill |
| 54 | `SINGLE_FIT_METER` | CHAR | 1 |  | Single FiT Meter |
| 55 | `MULTI_FIT_METER` | CHAR | 1 |  | Multiple FiT Meter |
| 56 | `FIT_CAPACITY_CHG` | CHAR | 1 |  | FiT Capacity Change |
| 57 | `NEW_FIT_METER` | CHAR | 1 |  | New FiT Meter Installed |
| 58 | `ZERO_FIT_PAYMENT` | CHAR | 1 |  | Zero FiT Payment |
| 59 | `NEW_FIT` | CHAR | 1 |  | New FiT |
| 60 | `EXIT_FIT` | CHAR | 1 |  | Exit FiT |
| 61 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
