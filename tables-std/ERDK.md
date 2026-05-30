# `ERDK`

**Description:** FI-CA Contract Document — financial contract document
**Category:** Standard SAP Table
**References:** 375 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/erdk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 60 fields | **Data types:** CHAR(42), CUKY(1), CURR(2), DATS(10), DEC(1), LANG(1), NUMC(2), TIMS(1)

## Key Fields
`PARTNER` | `VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DRUCKDAT` | DRUCKDAT | — | DATS | 8 | 0 | Print Date |
| `FAEDN` | FAEDN_KK | — | DATS | 8 | 0 | Due date for net payment |
| `FAEDS` | FAEDS_KK | — | DATS | 8 | 0 | Due Date for Cash Discount |
| `SKTPZ` | SKTPZ_KK | — | DEC | 5 | 3 | Cash discount rate |
| `BUDAT` | BUDAT | — | DATS | 8 | 0 | Posting Date in the Document |
| `BLDAT` | BLDAT | — | DATS | 8 | 0 | Document Date in Document |
| `STOKZ` | STOKZ | — | CHAR | 1 | 0 | Document Has Been Reversed |
| `INTOPBEL` | INTOPBEL | — | CHAR | 12 | 0 | Number of Print Document Used to Reverse Document |
| `ERDZ_V` | ERDZ_V | — | CHAR | 1 | 0 | ERDZ/ERDL exists for ERDK |
| `ERDR_V` | ERDR_V | — | CHAR | 1 | 0 | ERDR exists for ERDK |
| `ERDO_V` | ERDO_V | — | CHAR | 1 | 0 | ERDO exists for ERDK |
| `ERDB_V` | ERDB_V | — | CHAR | 1 | 0 | ERDB exists for ERDK |
| `ERDU_V` | ERDU_V | — | CHAR | 1 | 0 | ERDU exists for ERDK |
| `ERDTS_V` | ERDTS_V | — | CHAR | 1 | 0 | ERDTS exists for ERDK |
| `FICA_V` | FICA_V | — | CHAR | 1 | 0 | FI-CA Document Posted |
| `TOTAL_AMNT` | BETRW_KK | — | CURR | 13 | 2 | Amount in Transaction Currency with +/- Sign |
| `TOTAL_WAER` | BLWAE_KK | — | CUKY | 5 | 0 | Transaction Currency |
| `TOTAL_AMNT_USE` | TOTAL_AMNT_USE | — | CHAR | 2 | 0 | Indicator: Use of bill sum total |
| `PYMET` | PYMET_KK | — | CHAR | 1 | 0 | Payment Method |
| `ZSBTR` | E_ZSBTR | — | CURR | 13 | 2 | Total Amount from Bill Items in Payment Form |
| `ZLSCH` | FIDZT | T048X | CHAR | 1 | 0 | Form ID for Attached Payment Medium |
| `NRZAS` | NRZAS_KK | — | CHAR | 12 | 0 | Payment Form Number |
| `PARTNER` | BU_PARTNER | — | CHAR | 10 | 0 | Business Partner Number |
| `VKONT` | VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `PORTION` | PORTION | — | CHAR | 8 | 0 | Portion |
| `ABRVORG` | ABRVORG | — | CHAR | 2 | 0 | Billing Transaction |
| `FORMKEY` | FORMKEY | — | CHAR | 30 | 0 | Application form |
| `FIKEY` | FIKEY_KK | — | CHAR | 12 | 0 | Reconciliation Key for General Ledger |
| `TOBRELEASD` | TOBRELEASD | — | CHAR | 1 | 0 | Indicator: document not released yet |
| `SIMULATED` | SIMULATED | — | CHAR | 1 | 0 | Indicator: invoicing generates a simulated document |
| `INVOICED` | INVOICED | — | CHAR | 1 | 0 | Indicator: document posted |
| `ABWVK` | ABWVK_KK | — | CHAR | 12 | 0 | Alternative contract account for collective bills |
| `ABWBL` | ABWBL_KK | — | CHAR | 12 | 0 | Number of the substitute FI-CA document |
| `ERGRD` | ERGRD | — | CHAR | 2 | 0 | Reason for creating print document |
| `LANGU` | LANGU_ACC | T002 | LANG | 1 | 0 | Language in connection with the contract account |
| `INVOICING_PARTY` | INVOICING_PARTY | — | CHAR | 10 | 0 | Service Provider That Invoices the Contract |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |
| `VERART` | VERART_KK | — | CHAR | 3 | 0 | Clearing Type For Clearing Postings |
| `STO_BUDAT` | STO_BUDAT | — | DATS | 8 | 0 | Reversal Date of Original Document (Reversal Only) |
| `STO_OPBEL` | STO_OPBEL | — | CHAR | 12 | 0 | Document Number of Original Document (Only for Reversal) |
| `ICREASON` | BCREASON | — | CHAR | 2 | 0 | Reason for Reversal |
| `MAZAE` | MAZAE_KK | — | NUMC | 6 | 0 | Counter for several dunning notices to a business partner |
| `ITEMS_ARCHIVED` | ITEMS_ARCHIVED | — | CHAR | 1 | 0 | Line items are archived |
| `EXKID` | EXKID_KK | — | CHAR | 2 | 0 | Key Identification |
| `EXBEL` | EXBEL_KK | — | CHAR | 16 | 0 | Official Document Number |
| `MAZAE_ABS` | MAZAE_KK | — | NUMC | 6 | 0 | Counter for several dunning notices to a business partner |
| `PRINTLOCK` | E_PRINTLOCK | — | CHAR | 1 | 0 | Document is Blocked for Printing |
| `EDIDISPATCH` | E_EDIDISPATCH | — | CHAR | 1 | 0 | Transmit Print Document Via EDI |
| `EDISENDDATE` | EDISENDDAT | — | DATS | 8 | 0 | Generation Date of EDI for Print Document |
| `TAXDATE` | E_TAXDATE | — | DATS | 8 | 0 | Tax Determination Date |
| `CREATION_TIME` | E_CREATION_TIME | — | TIMS | 6 | 0 | Time of Print Document Creation |
| `BILLING_PERIOD` | E_BILLING_PERIOD | — | CHAR | 10 | 0 | Billing Key Date (For Example January 2002) |
| `OSB_GROUP` | E_OSB_GROUP | — | CHAR | 3 | 0 | On-Site Billing Group |
| `REVLOCK` | E_REVLOCK | — | CHAR | 1 | 0 | Reversal Block Indicator for Print Documents |
| `SEPA_PRENOT` | E_SEPA_PRENOT | — | CHAR | 1 | 0 | Invoicing Document Contains SEPA Pre-Notification |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `LANGU` | ERDK | LANGU | T002 |  | |
| `MANDT` | ERDK | MANDT | T000 |  | |
| `ZLSCH` | ERDK | MANDT | T048X |  | |
| `ZLSCH` | * |  | T048X |  | |
| `ZLSCH` | ERDK | ZLSCH | T048X |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BLDAT`, `BUDAT`, `DRUCKDAT`, `ERDAT`, `FICA_V`, `INTOPBEL`, `LOEVM`, `OPBEL`, `PARTNER`, `SIMULATED`, `STOKZ`, `VKONT`, `budat`, `erdat`, `fica_v`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BUDAT`, `ERDAT`, `OPBEL`, `budat`, `erdat`, `opbel`

## Join Paths
- `ERDK.OPBEL` → `DFKKKO.OPBEL` — FI-CA Doc → Doc Header

## Programs Using This Table
- `z_bapi_get_duedate.txt`
- `z_bapi_simple_accinfo.txt`
- `zisbi0006.txt`
- `zisbi0084.txt`
- `zisbi0086.txt`
- `zisbi0151.txt`
- `zisbi0201_tp.txt`
- `zisbi0219f01.txt`
- `zisbi0224_status_0200o01.txt`
- `zisbi0226_f01.txt`
- `zisbi_invoice_preview_ss.txt`
- `ziscs0148.txt`
- `ziscs0151.txt`
- `ziscs_migration_bill_segment.txt`
- `zisfi0083.txt`
- `zisfi0083_1t.txt`
- `zisfi0116_test3.txt`
- `zisfi0138.txt`
- `zisfi0139.txt`
- `zisfi0207.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_