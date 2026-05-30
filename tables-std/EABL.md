# `EABL`

**Description:** Installation Register — meter register at a device location
**Category:** Standard SAP Table
**References:** 540 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eabl/) — validated 2026-05-30, schema v1.0
**Schema fields:** 80 fields | **Data types:** CHAR(45), DATS(14), DEC(10), NUMC(9), UNIT(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `GERNR` | GERAET | — | CHAR | 18 | 0 | Device |
| `EQUNR` | EQUNR | EQUI | CHAR | 18 | 0 | Equipment Number |
| `ZWNUMMER` | E_ZWNUMMER | — | NUMC | 3 | 0 | Register |
| `ADAT` | ADAT | — | DATS | 8 | 0 | Meter reading date relevant to billing |
| `ATIM` | ATIM | — | CHAR | 4 | 0 | Meter reading time (relevant to billing) |
| `V_ZWSTAND` | V_ZWSTAND | — | DEC | 17 | 0 | Places Before Decimal Point in Meter Reading |
| `N_ZWSTAND` | N_ZWSTAND | — | DEC | 14 | 14 | Places After Decimal Point in the Meter Reading |
| `V_ZWSTNDAB` | V_ZWSTNDAB | — | DEC | 17 | 0 | Predecimal Places in Billed Meter Reading |
| `N_ZWSTNDAB` | N_ZWSTNDAB | — | DEC | 14 | 14 | Decimal Places in the Billed Meter Reading |
| `MASSREAD` | E_MASSREAD | T006 | UNIT | 3 | 0 | Unit of measurement for meter reading |
| `MASSBILL` | E_MASSBILL | T006 | UNIT | 3 | 0 | Unit of measurement for billing |
| `STANZVOR` | STANZVORE | — | NUMC | 2 | 0 | Number of predecimal places for register |
| `STANZNAC` | STANZNACE | — | NUMC | 2 | 0 | Number of decimal places for register |
| `SCHAEVER` | SCHAEVER | — | CHAR | 2 | 0 | Estimation procedure |
| `SCHAEGR` | SCHAEGR | TE567 | CHAR | 2 | 0 | Estimation reason |
| `AKTIV` | E_AKTIV | — | CHAR | 1 | 0 | Meter reading active |
| `ADATSOLL` | ADATSOLL | — | DATS | 8 | 0 | Scheduled meter reading date |
| `ADATMAX` | ADATMAX | — | DATS | 8 | 0 | Date of maximum meter reading |
| `ATIMMAX` | ATIMMAX | — | CHAR | 4 | 0 | Time of maximum meter reading |
| `ADATTATS` | ADATTATS | — | DATS | 8 | 0 | Actual meter reading date |
| `ATIMTATS` | ATIMTATS | — | CHAR | 4 | 0 | Actual meter reading time |
| `ADATERZ` | ADATERZ | — | DATS | 8 | 0 | Meter reading date of implausible meter reading result |
| `ATIMERZ` | ATIMERZ | — | CHAR | 4 | 0 | Meter reading time of implausible meter reading result |
| `ADATPROG` | ADATPROG | — | DATS | 8 | 0 | Meter reading date from which forecast is made |
| `ATIMPROG` | ATIMPROG | — | CHAR | 4 | 0 | Meter reading time from which consumption is determined |
| `ZUORDDAT` | E_ZUORDDAT | — | DATS | 8 | 0 | Meter reading allocation date |
| `THGDATUM` | THGDATUM | — | DATS | 8 | 0 | Gas allocation date |
| `PRUEFZAHL` | PRUEFZAHL | — | NUMC | 2 | 0 | Check number |
| `BAPERTYP` | BAPERTYP | — | CHAR | 1 | 0 | Base period category |
| `ABLSTAT` | ABLSTAT | — | CHAR | 1 | 0 | Meter Reading Status |
| `PRUEFPKT` | PRUEFPKT | TE218 | CHAR | 2 | 0 | Independent validation |
| `POPCODE` | POPCODE | TE625 | CHAR | 2 | 0 | Dependent validation |
| `PRUEFTYP` | PRUEFTYP | — | CHAR | 1 | 0 | Validation category for meter readings |
| `ABLHINW` | ABLHINW | TE259 | CHAR | 4 | 0 | Note from meter reader |
| `STABLHW` | STABLHW | — | CHAR | 2 | 0 | Control of follow-up action for MR result with MR note |
| `KONTRVRF` | KONTRVRF | — | CHAR | 1 | 0 | Indicator: dummy record from automatic control procedure |
| `ABLESART` | GEPLABL | TE614 | CHAR | 2 | 0 | Scheduled meter reading category |
| `ABLESER` | ABLESER | TE115 | CHAR | 3 | 0 | Meter reader number |
| `NACHERF` | NACHERF | — | CHAR | 1 | 0 | Meter reading result inserted or modified |
| `MDENR` | MDENR | — | NUMC | 3 | 0 | Number for mobile data entry (MDE) |
| `MDEUPL` | MDEDOWN | — | CHAR | 1 | 0 | Order has been output |
| `E_ZEITVBL` | E_ZEITVBL | — | CHAR | 1 | 0 | Multiple meter reading order creation |
| `E_ZVLZUORD` | E_ZVLZUORD | — | NUMC | 3 | 0 | Multiple allocation |
| `STEUERGRP` | STEUERGRP | TE629 | CHAR | 4 | 0 | Control group for multiple meter reading order creation |
| `ARBAUF` | ARBAUF | — | CHAR | 1 | 0 | Control Meter Reading Order ID Printed |
| `KSTATUS` | E_KSTATUS | — | CHAR | 1 | 0 | Status for automatic monitoring of meter reading order |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `ENTRYNUMB` | ENTRYNUMB | — | NUMC | 8 | 0 | Entry number for fast entry |
| `ACTOR` | HROBJEC_14 | — | CHAR | 14 | 0 | Concatenated Identification (Type and ID) of Org.Objects |
| `ISTABLART` | ISTABLART | TE436 | CHAR | 2 | 0 | Meter reading type |
| `ABLESTYP` | ABLESTYP | TE614 | CHAR | 2 | 0 | Meter reading category |
| `E_ZVBL_BEZDAT` | E_ZVBL_BEZDAT | — | DATS | 8 | 0 | Scheduled meter reading date for base meter reading |
| `SM_AUFNR` | PM_SVCNR | — | CHAR | 12 | 0 | Service order or notification |
| `DOC_TYPE` | KZ_SM_DOC_TYPE | — | CHAR | 1 | 0 | Document category for plant maintenance and customer service |
| `ADATREAL` | ADATREAL | — | DATS | 8 | 0 | [JBP] Real Meter Reading Date |
| `ATIMREAL` | ATIMREAL | — | CHAR | 4 | 0 | [JBP] Real Meter Reading Time |
| `S_ISTABLART` | S_ISTABLART | — | CHAR | 2 | 0 | [JBP] Meter Reading Type for Original Meter Reading |
| `S_AKTIV` | S_AKTIV | — | CHAR | 1 | 0 | [JBP] Orig. Meter Reading: Meter Reading Active |
| `S_ABLSTAT` | S_ABLSTAT | — | CHAR | 1 | 0 | [JBP] Original Meter Reading Status |
| `S_V_ZWSTAND` | S_V_ZWSTAND | — | DEC | 17 | 0 | [JBP] Orig. MR: Decimal Places Before Meter reading |
| `S_N_ZWSTAND` | S_N_ZWSTAND | — | DEC | 14 | 14 | [JBP] Decimal Places of Meter Readings for Original MR |
| `S_V_ZWSTNDAB` | S_V_ZWSTNDAB | — | DEC | 17 | 0 | [JBP] Predecimal Places of Billed MR for Original MR |
| `S_N_ZWSTNDAB` | S_N_ZWSTNDAB | — | DEC | 14 | 14 | [JBP] Decimal Places of Billed Orginal Meter Reading |
| `REMOVED` | REMOVED | — | CHAR | 1 | 0 | [JBP] Status Indicator: MR Result Suppressed |
| `BP` | BP | — | CHAR | 1 | 0 | Selection of Billing Period: Standard or JBP |
| `REM_ABLBELNR` | REM_ABLBELNR | — | CHAR | 20 | 0 | [JBP] Suppressed MR Document Number |
| `REM_ABLESER` | R_ABLESER | — | CHAR | 3 | 0 | Meter Reader Number of Suppressed Meter Reading |
| `S_ADATSOLL` | ADATSOLL | — | DATS | 8 | 0 | Scheduled meter reading date |
| `S_ZVBL_BEZDAT` | E_ZVBL_BEZDAT | — | DATS | 8 | 0 | Scheduled meter reading date for base meter reading |
| `AMS` | E_AMI_AMS | TEAMI_AMS | CHAR | 4 | 0 | Advanced Metering System |
| `TRANSSTAT` | E_AMI_MR_TRANSSTAT | ISU_F4_AMITRSTAT | CHAR | 5 | 0 | Transfer Status Code |
| `TRANSTSTAMP` | TIMESTAMPL | — | DEC | 21 | 7 | UTC Time Stamp in Long Form (YYYYMMDDhhmmssmmmuuun) |
| `SOURCESYST` | E_AMI_SOURCESYST | — | NUMC | 1 | 0 | Source System From Which Data is Requested |
| `QNT` | E_QD_QNT | — | DEC | 31 | 14 | Quantity Determined from Meter Reading in Internal Format |
| `QDSTAT` | E_QD_STAT | — | CHAR | 2 | 0 | Status of Quantity Determination |
| `QDPROC` | E_QD_PROC_MR | — | NUMC | 2 | 0 | Qty Determination Procedure During Meter Reading / Billing |
| `PREV_MRDOC` | E_QD_PREV_MRDOC | — | CHAR | 20 | 0 | Internal ID of Previous Meter Reading Result Document |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABLESART` | EABL | MANDT | TE614 |  | |
| `ABLESART` | EABL | ABLESART | TE614 |  | |
| `ABLESER` | EABL | MANDT | TE115 |  | |
| `ABLESER` | EABL | ABLESER | TE115 |  | |
| `ABLESTYP` | EABL | MANDT | TE614 |  | |
| `ABLESTYP` | EABL | ABLESTYP | TE614 |  | |
| `ABLHINW` | EABL | MANDT | TE259 |  | |
| `ABLHINW` | EABL | ABLHINW | TE259 |  | |
| `AMS` | * |  | TEAMI_AMS |  | |
| `AMS` | SYST | MANDT | TEAMI_AMS |  | |
| `AMS` | EABL | AMS | TEAMI_AMS |  | |
| `EQUNR` | EABL | MANDT | EQUI |  | |
| `EQUNR` | EABL | EQUNR | EQUI |  | |
| `ISTABLART` | EABL | MANDT | TE436 |  | |
| `ISTABLART` | EABL | ISTABLART | TE436 |  | |
| `MANDT` | EABL | MANDT | T000 |  | |
| `MASSBILL` | EABL | MASSBILL | T006 |  | |
| `MASSBILL` | EABL | MANDT | T006 |  | |
| `MASSREAD` | EABL | MANDT | T006 |  | |
| `MASSREAD` | EABL | MASSREAD | T006 |  | |
| `POPCODE` | EABL | POPCODE | TE625 |  | |
| `PRUEFPKT` | EABL | PRUEFPKT | TE218 |  | |
| `SCHAEGR` | EABL | MANDT | TE567 |  | |
| `SCHAEGR` | EABL | SCHAEGR | TE567 |  | |
| `STEUERGRP` | EABL | MANDT | TE629 |  | |
| `STEUERGRP` | EABL | STEUERGRP | TE629 |  | |
| `TRANSSTAT` | EABL | TRANSSTAT | ISU_F4_AMITRSTAT |  | |
| `TRANSSTAT` | SY | LANGU | ISU_F4_AMITRSTAT |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABLBELNR`, `ABLSTAT`, `ADAT`, `ATIM`, `EQUNR`, `GERNR`, `N_ZWSTAND`, `V_ZWSTAND`, `ZWNUMMER`, `ablbelnr`, `ablesart`, `ableser`, `ablestyp`, `ablhinw`, `ablstat`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `EQUNR`, `ablbelnr`, `ablstat`, `adat`, `adatsoll`, `aedat`, `equnr`, `gernr`, `zwnummer`

## Join Paths
- `EABL.ANLAGE` → `EANL.ANLAGE` — Register → Installation
- `EABL.EQUNR` → `EQUI.EQUNR` — Register → Equipment
- `EABL.ABLBELNR` → `EABLG.ABLBELNR` — Register → Register History

## Programs Using This Table
- `z_isdm_create_grpbill_chkread.txt`
- `ziscs0184.txt`
- `ziscs0273.txt`
- `ziscs0525_f01.txt`
- `ziscs_migration_estimate_read.txt`
- `zisdatveri.txt`
- `zisdm0116.txt`
- `zisdm0152.txt`
- `zisdm0159.txt`
- `zisdm0169.txt`
- `zisdm0170.txt`
- `zisdm0172.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0204f01.txt`
- `zisdm0215.txt`
- `zisdm0246.txt`
- `zisdm0272.txt`
- `zismd0038_recon.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_