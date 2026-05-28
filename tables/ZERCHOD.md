# ZERCHOD
**Description:** Screen fields for ZEA05 (New billing outsorting)
**Total Fields:** 90
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0042`
- `zisbi0042_1`
- `zisbi0042_2`
- `zisbi0042_newfm`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BELNR` | CHAR | 12 |  | Number of a billing document |
| 2 | `REMARKS` | CHAR | 100 |  | Remarks |
| 3 | `AEDAT` | DATS | 8 |  | Remarks date |
| 4 | `AETIM` | TIMS | 6 |  | Remarks time |
| 5 | `AENAM` | CHAR | 12 |  | Remarks by |
| 6 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 7 | `BPINFO` | CHAR | 132 |  | Text for business partner |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `VERTRAG` | CHAR | 10 |  | Contract |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `ANLART` | CHAR | 4 |  | Installation type |
| 13 | `PORTION` | CHAR | 8 |  | Portion |
| 14 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 15 | `KTOKLASSE` | CHAR | 4 |  | Account class |
| 16 | `.INCLUDE` | &nbsp; | 0 |  | Structure for Outsorting |
| 17 | `VALIDATION` | CHAR | 10 |  | Name of billing validation |
| 18 | `MANOUTSORT` | CHAR | 8 |  | Reason for manual outsorting in billing |
| 19 | `FREI_AM` | DATS | 8 |  | Document Release Date |
| 20 | `FREI_VON` | CHAR | 12 |  | Name of user who released the document |
| 21 | `DEVIATION` | DEC | 13 |  | Deviation |
| 22 | `SIMULATION` | CHAR | 2 |  | Indicator: billing simulation |
| 23 | `OUTCOUNT` | NUMC | 2 |  | Number of manual outsortings to be carried out yet |
| 24 | `STORNODAT` | DATS | 8 |  | Reversal date |
| 25 | `REVNAM` | CHAR | 12 |  | Reversed by |
| 26 | `SIMULATED` | CHAR | 1 |  | Indicator: simulated documents in outsorting |
| 27 | `BUKRS` | CHAR | 4 |  | Company Code |
| 28 | `SPARTE` | CHAR | 2 |  | Division |
| 29 | `CHILD` | CHAR | 1 |  | Child |
| 30 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 31 | `KOFIZ` | CHAR | 2 |  | Account determination ID for IS-U contracts |
| 32 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 33 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 34 | `ZUORDDAA` | DATS | 8 |  | Allocation date for billing |
| 35 | `BILLINGRUNNO` | CHAR | 12 |  | Number of Billing Run |
| 36 | `AUSGRUP` | CHAR | 8 |  | Outsorting check group for billing |
| 37 | `VALUE1` | DEC | 15 |  | Validation Parameter(s) |
| 38 | `VALUE2` | DEC | 15 |  | Validation Parameter(s) |
| 39 | `VALUE3` | DEC | 15 |  | Validation Parameter(s) |
| 40 | `VALUE4` | DEC | 15 |  | Validation Parameter(s) |
| 41 | `VALUE5` | CHAR | 10 |  | Validation Parameter(s) |
| 42 | `TOBRELEASD` | CHAR | 1 |  | Indicator: document not released yet |
| 43 | `%_COLOR` | CHAR | 3 |  | Color Code for ALV List |
| 44 | `BOX` | CHAR | 1 |  | Single-Character Flag |
| 45 | `MDUSREQUESTID` | CHAR | 22 |  | MDUS Request ID |
| 46 | `OSNAM` | CHAR | 12 |  | Outsort By |
| 47 | `IND` | CHAR | 2 |  | ZEA05 Indicator |
| 48 | `ADC` | DEC | 16 |  | Current ADC |
| 49 | `ADC_AVG` | DEC | 16 |  | Average ADC |
| 50 | `PER1` | DEC | 16 |  | % Change |
| 51 | `ADC1` | DEC | 16 |  | ADC (current bill -1) |
| 52 | `PER2` | DEC | 16 |  | % Change |
| 53 | `ADC2` | DEC | 16 |  | ADC (current bill - 2) |
| 54 | `PER3` | DEC | 16 |  | % Change |
| 55 | `ADC_LASTYR` | DEC | 16 |  | ADC for same period last year |
| 56 | `PER4` | DEC | 16 |  | % Change |
| 57 | `REVIEW` | CHAR | 1 |  | Send for Review |
| 58 | `USERID_LEVEL1` | CHAR | 12 |  | 1st Level user ID |
| 59 | `USERID_LEVEL2` | CHAR | 12 |  | 2nd Level User Id |
| 60 | `RDATE` | DATS | 8 |  | Date of Review |
| 61 | `MBAMOUNT` | DEC | 16 |  | Maximum Billing Amount |
| 62 | `MBAMOUNT_PER` | CHAR | 25 |  | Max Bill Amount % |
| 63 | `TOTKWH` | DEC | 16 |  | Current Total Consumption |
| 64 | `MAXTOTKWH` | DEC | 16 |  | Maximum Total Consumption |
| 65 | `MAXTOTKWH_PER` | CHAR | 25 |  | Max. kWh (%) |
| 66 | `CONPKWH` | CHAR | 25 |  | Current On-Peak Consumption |
| 67 | `MONPKWH` | CHAR | 25 |  | Maximum On-Peak Consumption |
| 68 | `ONPKWH_PER` | CHAR | 25 |  | Max. On-Peak kWh (%) |
| 69 | `COFFPKWH` | CHAR | 25 |  | Current Off-Peak Consumption |
| 70 | `MOFFPKWH` | CHAR | 25 |  | Maximum Off-Peak Consumption |
| 71 | `OFFPKWH_PER` | CHAR | 25 |  | Max. Off-Peak kWh (%) |
| 72 | `MADC` | DEC | 16 |  | Maximum ADC |
| 73 | `MADC_PER` | CHAR | 25 |  | Max. ADC (%) |
| 74 | `CONPKVA` | CHAR | 25 |  | Current On-Peak Billing Demand |
| 75 | `MONPKVA` | CHAR | 25 |  | Maximum On-Peak Billing Demand |
| 76 | `ONPKVA_PER` | CHAR | 25 |  | Max. On-Peak kVA (%) |
| 77 | `COFFPKVA` | CHAR | 25 |  | Current Off-Peak Billing Demand |
| 78 | `MOFFPKVA` | CHAR | 25 |  | Maximum Off-Peak Billing Demand |
| 79 | `OFFPKVA_PER` | CHAR | 25 |  | Max. Off-Peak kVA (%) |
| 80 | `CTPKWH` | CHAR | 25 |  | Current Total Projected Consumption |
| 81 | `MPTKWH` | CHAR | 25 |  | Maximum Projected Total Consumption |
| 82 | `TPKWH_PER` | CHAR | 25 |  | Max. Proj. kWh (%) |
| 83 | `FIT_IND` | CHAR | 1 |  | FiT Indicator |
| 84 | `NEWMI` | CHAR | 1 |  | New Move-In |
| 85 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 86 | `CONS_EST` | CHAR | 1 |  | Consecutive Estimate |
| 87 | `MTH_CONS_EST` | CHAR | 5 |  | Month with Consecutive Estimate |
| 88 | `EST_ACT` | CHAR | 1 |  | Estimated/Actual |
| 89 | `DUNLOCK` | CHAR | 1 |  | Dunning Lock |
| 90 | `APPR_STATUS` | CHAR | 1 |  | Approval Status |
