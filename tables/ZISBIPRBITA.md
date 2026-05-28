# ZISBIPRBITA
**Description:** Print Document, Bill Type, & Tariff Type Mapping Table
**Total Fields:** 80
**Key Fields:** MANDT, DATUM1, OPBEL, TIME1, USER1

## Programs Using This Table
- `zis_consumption_history=======ft`
- `zis_insert_statistics=========ft`
- `zisbi0001`
- `zisbi0020`
- `zisbi0033`
- `zisbi0043`
- `zisbi0043n`
- `zisbi0069`
- `zisbi0082`
- `zisbi0136`
- `zisbi0256`
- `zisbi0270`
- `zisbi0270t`
- `zisdm0431`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM1` | DATS | 8 | 🔑 | Date |
| 3 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 4 | `TIME1` | TIMS | 6 | 🔑 | System Time |
| 5 | `USER1` | CHAR | 12 | 🔑 | User Name |
| 6 | `ZZBILLID` | CHAR | 2 |  | Bill ID |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 9 | `ZZRECIPIENT` | CHAR | 1 |  | Recipient |
| 10 | `ZZDELIVERY` | CHAR | 1 |  | Delivery Method |
| 11 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 12 | `SPOOL` | CHAR | 4 |  | Spool: Output device |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `BATCH` | NUMC | 10 |  | Batch Number |
| 15 | `MIN_CHARGE` | CHAR | 1 |  | Minimum Charge |
| 16 | `FULL_RATE` | CHAR | 1 |  | Full Rate |
| 17 | `WATER_HEATER` | CHAR | 1 |  | Water Heater |
| 18 | `AUTO_ADJ` | CHAR | 1 |  | Auto Adjusted |
| 19 | `CHILD` | CHAR | 1 |  | Child |
| 20 | `PRO_RATA` | CHAR | 1 |  | Pro rata |
| 21 | `LANGU` | LANG | 1 |  | Language Key |
| 22 | `FINAL` | CHAR | 1 |  | Final |
| 23 | `AMENDED` | CHAR | 1 |  | Amended |
| 24 | `BLOCK1` | CHAR | 1 |  | Block 1 |
| 25 | `BLOCK2` | CHAR | 1 |  | Block 2 |
| 26 | `BLOCK3` | CHAR | 1 |  | Block 3 |
| 27 | `KVA_BLOCK1` | CHAR | 1 |  | KVA Block 1 |
| 28 | `KVA_BLOCK2` | CHAR | 1 |  | KVA Block 2 |
| 29 | `KWH_BLOCK1` | CHAR | 1 |  | KWH Block 1 |
| 30 | `KWH_BLOCK2` | CHAR | 1 |  | KWH Block 2 |
| 31 | `HLFR_BLOCK1` | CHAR | 1 |  | HLFR Block 1 |
| 32 | `HLFR_BLOCK2` | CHAR | 1 |  | HLFR Block 2 |
| 33 | `KVA_MIN` | CHAR | 1 |  | KVA Min |
| 34 | `KVA_OFF_GT_ON` | CHAR | 1 |  | KVA Off > On |
| 35 | `KWH_OFF_GT_ON` | CHAR | 1 |  | KWH Off > On |
| 36 | `KWH_OFF_PEAK` | CHAR | 1 |  | KWH Off Peak |
| 37 | `KVA_WAIVE` | CHAR | 1 |  | KVA Waive |
| 38 | `KVA_SHORTFALL` | CHAR | 1 |  | KVA Shortfall |
| 39 | `DELIVERY_CHARGE` | CHAR | 1 |  | Delivery Charge |
| 40 | `FREE_UNIT` | CHAR | 1 |  | Free Unit |
| 41 | `INITIAL_CHARGE` | CHAR | 1 |  | Initial Charge |
| 42 | `HIGH_VOLT_RIDER` | CHAR | 1 |  | High Voltage Rider |
| 43 | `INCLUSIVE_UNIT` | CHAR | 1 |  | Inclusive Unit |
| 44 | `LP_BILLING` | CHAR | 1 |  | Load Profile Billing |
| 45 | `CB_BILLING` | CHAR | 1 |  | Complex Billing |
| 46 | `DOCODE` | CHAR | 3 |  | District Office Code (obsolete) |
| 47 | `PBCODE` | CHAR | 12 |  | Postman Beat Code (obsolete) |
| 48 | `MONTH_BILL_ACT` | CHAR | 1 |  | Monthly Opt-In Bill (Actual) |
| 49 | `MONTH_BILL_EST` | CHAR | 1 |  | Monthly Opt-In Bill (Estimate) |
| 50 | `AMI_CUST_GRP` | CHAR | 8 |  | Current DSM Group for CA |
| 51 | `AMI_MTR_CONNECTED` | CHAR | 1 |  | AMI meter conencted |
| 52 | `PD_WITH_TOU` | CHAR | 1 |  | Indicator for printdoc contains TOU line item |
| 53 | `PD_WITH_PTR` | CHAR | 1 |  | Indicator for printdoc contains PTR line item |
| 54 | `SINGLE_FIT_METER` | CHAR | 1 |  | Single FiT Meter |
| 55 | `MULTI_FIT_METER` | CHAR | 1 |  | Multiple FiT Meter |
| 56 | `FIT_CAPACITY_CHG` | CHAR | 1 |  | FiT Capacity Change |
| 57 | `NEW_FIT_METER` | CHAR | 1 |  | New FiT Meter Installed |
| 58 | `ZERO_FIT_PAYMENT` | CHAR | 1 |  | Zero FiT Payment |
| 59 | `NEW_FIT` | CHAR | 1 |  | New FiT |
| 60 | `EXIT_FIT` | CHAR | 1 |  | Exit FiT |
| 61 | `REBILL_FLAG` | CHAR | 1 |  | Re Bill Flag |
| 62 | `MSTR_METER` | CHAR | 1 |  | Master Meter |
| 63 | `SUB_METER` | CHAR | 1 |  | Sub Meter |
| 64 | `SHORTBILL` | CHAR | 1 |  | Short Bill |
| 65 | `LONGBILL` | CHAR | 1 |  | Long Bill |
| 66 | `DEVELOPER` | CHAR | 1 |  | Developer Bill |
| 67 | `UNMETER` | CHAR | 1 |  | Un-meterd Bill |
| 68 | `MULTI_RATECAT` | CHAR | 1 |  | Multiple Rate Category |
| 69 | `DDA` | CHAR | 1 |  | Direct Debit Account |
| 70 | `CCA` | CHAR | 1 |  | Credit Card Autopay Account |
| 71 | `NON_AUTOPAY` | CHAR | 1 |  | Non Autopay Account |
| 72 | `FURTHERDEPOSIT` | CHAR | 1 |  | Further Deposit |
| 73 | `LATEP_CHARGE` | CHAR | 1 |  | Late Payment Charge |
| 74 | `CON_EST` | CHAR | 1 |  | Consecutive Estimate |
| 75 | `ESTIMATE` | CHAR | 1 |  | Estimate |
| 76 | `BILL_51` | CHAR | 1 |  | 5+1 Billing |
| 77 | `BI_MTHLY` | CHAR | 1 |  | BI-Monthly |
| 78 | `SSR_REB` | CHAR | 1 |  | SSR Rebate |
| 79 | `PD_WITH_TOU_PTR` | CHAR | 1 |  | PD with TOU & PTR |
| 80 | `KVA_MIN_SUMMER` | CHAR | 1 |  | KVA Min (Summer) |
