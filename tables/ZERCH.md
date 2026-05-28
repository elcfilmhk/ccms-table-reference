# ZERCH
**Description:** Copy of Billing Doc. Data
**Total Fields:** 97
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zisbi0214`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `BUKRS` | CHAR | 4 |  | Company Code |
| 4 | `SPARTE` | CHAR | 2 |  | Division |
| 5 | `GPARTNER` | CHAR | 10 |  | Business Partner Number |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `VERTRAG` | CHAR | 10 |  | Contract |
| 8 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 9 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 10 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
| 11 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 12 | `PTERMTDAT` | DATS | 8 |  | End of billing period from schedule record of portion |
| 13 | `BELEGDAT` | DATS | 8 |  | Creation date of billing document |
| 14 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 15 | `BELNRALT` | CHAR | 12 |  | Number of previous document |
| 16 | `STORNODAT` | DATS | 8 |  | Reversal date |
| 17 | `ABRVORG` | CHAR | 2 |  | Billing Transaction |
| 18 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 19 | `KOFIZ` | CHAR | 2 |  | Account determination ID for IS-U contracts |
| 20 | `PORTION` | CHAR | 8 |  | Portion |
| 21 | `FORMULAR` | CHAR | 16 |  | Form name |
| 22 | `SIMULATION` | CHAR | 2 |  | Indicator: billing simulation |
| 23 | `BELEGART` | CHAR | 2 |  | Document type |
| 24 | `BERGRUND` | CHAR | 2 |  | Reason for credit memo/backbilling |
| 25 | `BEGNACH` | DATS | 8 |  | Start of backbilling period |
| 26 | `TOBRELEASD` | CHAR | 1 |  | Indicator: document not released yet |
| 27 | `TXJCD` | CHAR | 15 |  | Tax Jurisdiction |
| 28 | `KONZVER` | CHAR | 10 |  | Franchise contract |
| 29 | `EROETIM` | CHAR | 4 |  | Time of day billing document was created |
| 30 | `ERCHO_V` | CHAR | 1 |  | ERCHO exists for ERCH |
| 31 | `ERCHZ_V` | CHAR | 1 |  | ERCHZ exists for ERCH |
| 32 | `ERCHU_V` | CHAR | 1 |  | ERCHU exists for ERCH |
| 33 | `ERCHR_V` | CHAR | 1 |  | ERCHR exists for ERCH |
| 34 | `ERCHC_V` | CHAR | 1 |  | ERCHC exists for ERCH |
| 35 | `ERCHV_V` | CHAR | 1 |  | ERCHV exists for ERCH |
| 36 | `ERCHT_V` | CHAR | 1 |  | ERCHT exists for ERCH |
| 37 | `ERCHP_V` | CHAR | 1 |  | ERCHP exists for ERCH |
| 38 | `ERCHE_V` | CHAR | 1 |  | ERCHE Available for ERCH |
| 39 | `ABRVORG2` | CHAR | 2 |  | Billing Transaction that Triggered Period-End Billing |
| 40 | `ABLEINH` | CHAR | 8 |  | Meter Reading Unit |
| 41 | `ENDPRIO` | CHAR | 1 |  | Priority of Period-End Billing |
| 42 | `.INCLUDE` | &nbsp; | 0 |  | Creation and Change Data (Author, Group and Deletion Flag) |
| 43 | `.INCLUDE` | &nbsp; | 0 |  | Creation and Change Data |
| 44 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 45 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 46 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 47 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 48 | `BEGRU` | CHAR | 4 |  | Authorization Group |
| 49 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 50 | `ABRDATSU` | DATS | 8 |  | Scheduled billing date for suppressed billing order |
| 51 | `ABRVORGU` | CHAR | 2 |  | Billing Transaction for a Suppressed Billing Order |
| 52 | `N_INVSEP` | CHAR | 1 |  | Only invoice document jointly with automatic document |
| 53 | `ABPOPBEL` | CHAR | 12 |  | Budget billing plan |
| 54 | `MANBILLREL` | CHAR | 1 |  | Manual Document Released for Invoicing |
| 55 | `BACKBI` | CHAR | 1 |  | Type of backbilling |
| 56 | `PERENDBI` | CHAR | 1 |  | Type of period-end billing |
| 57 | `NUMPERBB` | INT1 | 3 |  | Number of periods for backbilling |
| 58 | `BEGEND` | DATS | 8 |  | Start of period-end billing period |
| 59 | `ENDOFBB` | CHAR | 1 |  | Indicator: end of backbilling period |
| 60 | `ENDOFPEB` | CHAR | 1 |  | Indicator: end of period-end billing period |
| 61 | `NUMPERPEB` | INT1 | 3 |  | Number of periods for period-end billing |
| 62 | `SC_BELNR_H` | CHAR | 12 |  | Number of billing document in adjustment reversal |
| 63 | `SC_BELNR_N` | CHAR | 12 |  | New billing document number in adjustment reversal |
| 64 | `ZUORDDAA` | DATS | 8 |  | Allocation date for billing |
| 65 | `BILLINGRUNNO` | CHAR | 12 |  | Number of Billing Run |
| 66 | `SIMRUNID` | CHAR | 8 |  | Simulation Period ID |
| 67 | `KTOKLASSE` | CHAR | 4 |  | Account class |
| 68 | `ORIGDOC` | CHAR | 2 |  | Origin of Billing Document |
| 69 | `NOCANC` | CHAR | 1 |  | Indicator: do not execute billing reversal |
| 70 | `ABSCHLPAN` | CHAR | 1 |  | Adjust budget billing plan |
| 71 | `MEM_OPBEL` | CHAR | 12 |  | Reversed invoicing document no. for new billing/invoicing |
| 72 | `MEM_BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 73 | `EXBILLDOCNO` | CHAR | 20 |  | External document number |
| 74 | `BCREASON` | CHAR | 2 |  | Reason for Reversal |
| 75 | `NINVOICE` | CHAR | 1 |  | Billing document without invoicing |
| 76 | `NBILLREL` | CHAR | 1 |  | Not relevant to billing |
| 77 | `CORRECTION_DATE` | DATS | 8 |  | Date when the Error Was Detected |
| 78 | `BASDYPER` | CHAR | 2 |  | Basic category of dynamic period control |
| 79 | `ESTINBILL` | CHAR | 2 |  | Meter Reading Results are Estimated in Billing |
| 80 | `ESTINBILLU` | CHAR | 2 |  | ESTINBILL of a Suppressed Billing Order |
| 81 | `ESTINBILL_SAV` | CHAR | 2 |  | Original Value from ESTINBILL |
| 82 | `ESTINBILL_USAV` | CHAR | 2 |  | ESTINBILL_SAV of a Suppressed Billing Order |
| 83 | `ACTPERIOD` | CHAR | 4 |  | Category of a period for current billing |
| 84 | `ACTPERORG` | CHAR | 4 |  | Original Category of a Current Period to be Billed |
| 85 | `EZAWE` | CHAR | 1 |  | Incoming Payment Method |
| 86 | `DAUBUCH` | CHAR | 1 |  | Standing order |
| 87 | `FDGRP` | CHAR | 10 |  | Planning Group |
| 88 | `BILLING_PERIOD` | CHAR | 10 |  | Billing Key Date (For Example January 2002) |
| 89 | `OSB_GROUP` | CHAR | 3 |  | On-Site Billing Group |
| 90 | `.INCLUDE` | &nbsp; | 0 |  | Special ERCH Fields for JBP (Japanese Billing Period) |
| 91 | `BP_BILL` | CHAR | 1 |  | Resulting Billing Period |
| 92 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 93 | `MAINDOCNO` | CHAR | 12 |  | Billing Document Number of Primary Installation |
| 94 | `INSTGRTYPE` | CHAR | 4 |  | Grouping Type for Installation Group |
| 95 | `INSTROLE` | CHAR | 4 |  | Role of an Installation Within the Installation Group |
| 96 | `MDUSREQUESTID` | CHAR | 22 |  | MDUS Request ID |
| 97 | `ASBACH_REL` | CHAR | 1 |  | Change to Assessment Basic Relevant |
