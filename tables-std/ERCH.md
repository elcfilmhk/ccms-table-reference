# `ERCH`

**Description:** Billing Document — invoice/bill header
**Category:** Standard SAP Table
**References:** 301 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/erch/) — validated 2026-05-30, schema v1.0
**Schema fields:** 91 fields | **Data types:** CHAR(74), DATS(15), INT1(2)

## Key Fields
`BUKRS` | `VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `SPARTE` | SPARTE | TSPA | CHAR | 2 | 0 | Division |
| `GPARTNER` | BU_PARTNER | — | CHAR | 10 | 0 | Business Partner Number |
| `VKONT` | VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `VERTRAG` | VERTRAG | — | CHAR | 10 | 0 | Contract |
| `BEGABRPE` | BEGABRPE | — | DATS | 8 | 0 | Start of billing period |
| `ENDABRPE` | ENDABRPE | — | DATS | 8 | 0 | End of billing period |
| `ABRDATS` | ABRDATS | — | DATS | 8 | 0 | Scheduled Billing Date |
| `ADATSOLL` | ADATSOLL | — | DATS | 8 | 0 | Scheduled meter reading date |
| `PTERMTDAT` | PTERMTDAT | — | DATS | 8 | 0 | End of billing period from schedule record of portion |
| `BELEGDAT` | BELEGDAT | — | DATS | 8 | 0 | Creation date of billing document |
| `ABWVK` | ABWVK_KK | — | CHAR | 12 | 0 | Alternative contract account for collective bills |
| `BELNRALT` | BELNRALT | — | CHAR | 12 | 0 | Number of previous document |
| `STORNODAT` | STORNODAT | — | DATS | 8 | 0 | Reversal date |
| `ABRVORG` | ABRVORG | — | CHAR | 2 | 0 | Billing Transaction |
| `HVORG` | HVORG_KK | TFKHVO | CHAR | 4 | 0 | Main Transaction for Line Item |
| `KOFIZ` | E_KOFIZ | TE097 | CHAR | 2 | 0 | Account determination ID for IS-U contracts |
| `PORTION` | PORTION | TE420 | CHAR | 8 | 0 | Portion |
| `FORMULAR` | TDFORM | — | CHAR | 16 | 0 | Form Name |
| `SIMULATION` | SIMULATION | — | CHAR | 2 | 0 | Indicator: billing simulation |
| `BELEGART` | E_BELART | TE093 | CHAR | 2 | 0 | Document type |
| `BERGRUND` | BERGRUND | — | CHAR | 2 | 0 | Reason for credit memo/backbilling |
| `BEGNACH` | BEGNACH | — | DATS | 8 | 0 | Start of backbilling period |
| `TOBRELEASD` | TOBRELEASD | — | CHAR | 1 | 0 | Indicator: document not released yet |
| `TXJCD` | TXJCD | — | CHAR | 15 | 0 | Tax Jurisdiction |
| `KONZVER` | KONZVER | — | CHAR | 10 | 0 | Franchise contract |
| `EROETIM` | EROETIM | — | CHAR | 4 | 0 | Time of day billing document was created |
| `ERCHO_V` | ERCHO_V | — | CHAR | 1 | 0 | ERCHO exists for ERCH |
| `ERCHZ_V` | ERCHZ_V | — | CHAR | 1 | 0 | ERCHZ exists for ERCH |
| `ERCHU_V` | ERCHU_V | — | CHAR | 1 | 0 | ERCHU exists for ERCH |
| `ERCHR_V` | ERCHR_V | — | CHAR | 1 | 0 | ERCHR exists for ERCH |
| `ERCHC_V` | ERCHC_V | — | CHAR | 1 | 0 | ERCHC exists for ERCH |
| `ERCHV_V` | ERCHV_V | — | CHAR | 1 | 0 | ERCHV exists for ERCH |
| `ERCHT_V` | ERCHT_V | — | CHAR | 1 | 0 | ERCHT exists for ERCH |
| `ERCHP_V` | ERCHP_V | — | CHAR | 1 | 0 | ERCHP exists for ERCH |
| `ERCHE_V` | ERCHE_V | — | CHAR | 1 | 0 | ERCHE Available for ERCH |
| `ABRVORG2` | ABRVORG2 | — | CHAR | 2 | 0 | Billing Transaction that Triggered Period-End Billing |
| `ABLEINH` | ABLEINHEIT | — | CHAR | 8 | 0 | Meter Reading Unit |
| `ENDPRIO` | ENDPRIO | — | CHAR | 1 | 0 | Priority of Period-End Billing |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |
| `ABRDATSU` | ABRDATSU | — | DATS | 8 | 0 | Scheduled billing date for suppressed billing order |
| `ABRVORGU` | ABRVORGU | — | CHAR | 2 | 0 | Billing Transaction for a Suppressed Billing Order |
| `N_INVSEP` | N_INVSEP | — | CHAR | 1 | 0 | Only invoice document jointly with automatic document |
| `ABPOPBEL` | ABPLANNR | — | CHAR | 12 | 0 | Budget billing plan |
| `MANBILLREL` | MANBILLREL | — | CHAR | 1 | 0 | Manual Document Released for Invoicing |
| `BACKBI` | BACKBI | — | CHAR | 1 | 0 | Type of backbilling |
| `PERENDBI` | PERENDBI | — | CHAR | 1 | 0 | Type of period-end billing |
| `NUMPERBB` | NUMPERBB | — | INT1 | 3 | 0 | Number of periods for backbilling |
| `BEGEND` | BEGEND | — | DATS | 8 | 0 | Start of period-end billing period |
| `ENDOFBB` | ENDOFBB | — | CHAR | 1 | 0 | Indicator: end of backbilling period |
| `ENDOFPEB` | ENDOFPEB | — | CHAR | 1 | 0 | Indicator: end of period-end billing period |
| `NUMPERPEB` | NUMPERPEB | — | INT1 | 3 | 0 | Number of periods for period-end billing |
| `SC_BELNR_H` | SC_BELNR | — | CHAR | 12 | 0 | Number of billing document in adjustment reversal |
| `SC_BELNR_N` | SC_BEL_N | — | CHAR | 12 | 0 | New billing document number in adjustment reversal |
| `ZUORDDAA` | E_ZUORDDATABR | — | DATS | 8 | 0 | Allocation date for billing |
| `BILLINGRUNNO` | BILLINGRUNNO | — | CHAR | 12 | 0 | Number of Billing Run |
| `SIMRUNID` | SIMRUNID | — | CHAR | 8 | 0 | Simulation Period ID |
| `KTOKLASSE` | KTOKLASSE | — | CHAR | 4 | 0 | Account class |
| `ORIGDOC` | ORIGDOC | — | CHAR | 2 | 0 | Origin of Billing Document |
| `NOCANC` | NOCANC | — | CHAR | 1 | 0 | Indicator: do not execute billing reversal |
| `ABSCHLPAN` | ABSCHLPAN | — | CHAR | 1 | 0 | Adjust budget billing plan |
| `MEM_OPBEL` | MEM_OPBEL | — | CHAR | 12 | 0 | Reversed invoicing document no. for new billing/invoicing |
| `MEM_BUDAT` | MEM_BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `EXBILLDOCNO` | EXBILLDOCNO | — | CHAR | 20 | 0 | External document number |
| `BCREASON` | BCREASON | TE272 | CHAR | 2 | 0 | Reason for Reversal |
| `NINVOICE` | NINVOICE | — | CHAR | 1 | 0 | Billing document without invoicing |
| `NBILLREL` | NBILLREL | — | CHAR | 1 | 0 | Not relevant to billing |
| `CORRECTION_DATE` | ISU_CORRECTION_DATE | — | DATS | 8 | 0 | Date when the Error Was Detected |
| `BASDYPER` | BASDYPER | — | CHAR | 2 | 0 | Basic category of dynamic period control |
| `ESTINBILL` | ESTINBILL | — | CHAR | 2 | 0 | Meter Reading Results are Estimated in Billing |
| `ESTINBILLU` | ESTINBILLU | — | CHAR | 2 | 0 | ESTINBILL of a Suppressed Billing Order |
| `ESTINBILL_SAV` | ESTINBILL_SAV | — | CHAR | 2 | 0 | Original Value from ESTINBILL |
| `ESTINBILL_USAV` | ESTINBILL_USAV | — | CHAR | 2 | 0 | ESTINBILL_SAV of a Suppressed Billing Order |
| `ACTPERIOD` | ACTPERIOD | — | CHAR | 4 | 0 | Category of a period for current billing |
| `ACTPERORG` | ACTPERORG | — | CHAR | 4 | 0 | Original Category of a Current Period to be Billed |
| `EZAWE` | EZAWE_KK | — | CHAR | 1 | 0 | Incoming Payment Method |
| `DAUBUCH` | DAUBUCH | — | CHAR | 1 | 0 | Standing order |
| `FDGRP` | FDGRP_KK | — | CHAR | 10 | 0 | Planning Group |
| `BILLING_PERIOD` | E_BILLING_PERIOD | — | CHAR | 10 | 0 | Billing Key Date (For Example January 2002) |
| `OSB_GROUP` | E_OSB_GROUP | TE555 | CHAR | 3 | 0 | On-Site Billing Group |
| `BP_BILL` | BP_BILL | — | CHAR | 1 | 0 | Resulting Billing Period |
| `MAINDOCNO` | MAINDOCNO | — | CHAR | 12 | 0 | Billing Document Number of Primary Installation |
| `INSTGRTYPE` | INSTGRTYPE | — | CHAR | 4 | 0 | Grouping Type for Installation Group |
| `INSTROLE` | INSTROLE | — | CHAR | 4 | 0 | Role of an Installation Within the Installation Group |
| `MDUSREQUESTID` | E_MDUSREQUESTID | EMDUSDRQHEAD | CHAR | 22 | 0 | MDUS Request ID |
| `ASBACH_REL` | ASBACH_REL | — | CHAR | 1 | 0 | Change to Assessment Basic Relevant |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BCREASON` | ERCH | MANDT | TE272 |  | |
| `BCREASON` | ERCH | BCREASON | TE272 |  | |
| `BELEGART` | ERCH | BELEGART | TE093 |  | |
| `BELEGART` | ERCH | MANDT | TE093 |  | |
| `BUKRS` | ERCH | MANDT | T001 |  | |
| `BUKRS` | ERCH | BUKRS | T001 |  | |
| `HVORG` | ERCH | MANDT | TFKHVO |  | |
| `HVORG` | &#039;R&#039; |  | TFKHVO |  | |
| `HVORG` | ERCH | HVORG | TFKHVO |  | |
| `KOFIZ` | ERCH | MANDT | TE097 |  | |
| `KOFIZ` | ERCH | BUKRS | TE097 |  | |
| `KOFIZ` | ERCH | SPARTE | TE097 |  | |
| `KOFIZ` | ERCH | KOFIZ | TE097 |  | |
| `MANDT` | ERCH | MANDT | T000 |  | |
| `MDUSREQUESTID` | ERCH | MANDT | EMDUSDRQHEAD |  | |
| `MDUSREQUESTID` | ERCH | MDUSREQUESTID | EMDUSDRQHEAD |  | |
| `OSB_GROUP` | ERCH | OSB_GROUP | TE555 |  | |
| `OSB_GROUP` | ERCH | MANDT | TE555 |  | |
| `PORTION` | ERCH | MANDT | TE420 |  | |
| `PORTION` | ERCH | PORTION | TE420 |  | |
| `SPARTE` | ERCH | MANDT | TSPA |  | |
| `SPARTE` | ERCH | SPARTE | TSPA |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABRVORG`, `AEDAT`, `BCREASON`, `BELEGART`, `BELNR`, `ENDABRPE`, `ERDAT`, `HVORG`, `SC_BELNR_H`, `SC_BELNR_N`, `TOBRELEASD`, `VERTRAG`, `VKONT`, `ableinh`, `abrdats`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BELEGART`, `BELNR`, `VERTRAG`, `ableinh`, `abrvorg`, `belnr`, `endabrpe`, `erdat`, `vertrag`, `vkont`

## Join Paths
- `ERCH.BELNR` → `ERCHC.BELNR` — Bill Doc → Bill Doc Line
- `ERCH.OPBEL` → `ERDK.OPBEL` — Bill Doc → FI-CA Doc

## Programs Using This Table
- `z_iscrm_check_ami_end.txt`
- `z_select_rfi38_data.txt`
- `zisbi0011.txt`
- `zisbi0057.txt`
- `zisbi0091.txt`
- `zisbi0099.txt`
- `zisbi0110.txt`
- `zisbi0214f01.txt`
- `zisbi0224_status_0200o01.txt`
- `zisbi0226_f01.txt`
- `zisbi239f01.txt`
- `zisbi_upd_ind.txt`
- `zisdm0089.txt`
- `zisdm0091.txt`
- `zisdm0170.txt`
- `zisdm0172.txt`
- `zisdm0183.txt`
- `zisdm0201.txt`
- `zisdm0278.txt`
- `zisfi0113_upd.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_