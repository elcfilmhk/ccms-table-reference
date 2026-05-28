# ZISDH_METER_DTL
**Description:** MR data retrieved during Download
**Total Fields:** 38
**Key Fields:** _none_

## Programs Using This Table
- `z_meter_task_fetch============ft`
- `z_transfer_meter_task_to_cs===ft`
- `zisdh0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CALLID` | CHAR | 40 |  | CallID |
| 2 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 3 | `GERNR` | CHAR | 18 |  | Serial Number |
| 4 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 5 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 6 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 7 | `MAIN_MRU` | CHAR | 8 |  | Meter reading together with allocated main MR unit |
| 8 | `MR_METHOD` | CHAR | 30 |  | Characteristic Value |
| 9 | `SM_AUFNR` | CHAR | 12 |  | Service order or notification |
| 10 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 13 | `CUST_MRR` | CHAR | 2 |  | Meter reading reason |
| 14 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 15 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 16 | `ABLSTAT` | CHAR | 1 |  | Meter Reading Status |
| 17 | `ABLESTYP` | CHAR | 2 |  | Meter reading category |
| 18 | `EQART` | CHAR | 10 |  | Type of Technical Object |
| 19 | `TYPBZ` | CHAR | 20 |  | Manufacturer model number |
| 20 | `ADATREAL` | DATS | 8 |  | [JBP] Real Meter Reading Date |
| 21 | `ATIMREAL` | CHAR | 4 |  | [JBP] Real Meter Reading Time |
| 22 | `BP` | CHAR | 1 |  | Selection of Billing Period: Standard or JBP |
| 23 | `ZUORDDAT` | DATS | 8 |  | Meter reading allocation date |
| 24 | `ABLHINW` | CHAR | 4 |  | Note from meter reader |
| 25 | `PHYSINST` | CHAR | 10 |  | Installation |
| 26 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 27 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 28 | `SEQNO` | NUMC | 8 |  | Route sequence number for each record |
| 29 | `RESET_DEMAND` | CHAR | 1 |  | TOU Reset Demand Indicator |
| 30 | `HISTBIS` | DATS | 8 |  | Meter reading date relevant to billing |
| 31 | `HISTAB` | DATS | 8 |  | Meter reading date relevant to billing |
| 32 | `MAINT_ACT_TYPE` | CHAR | 3 |  | Maintenance activity type |
| 33 | `EARLY_START` | DATS | 8 |  | Scheduled meter reading date |
| 34 | `PORTION` | CHAR | 8 |  | Portion |
| 35 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 36 | `MONTH_START` | DATS | 8 |  | System Date |
| 37 | `MONTH_END` | DATS | 8 |  | System Date |
| 38 | `REGISTER` | TTYP | 0 |  | Register Details |
