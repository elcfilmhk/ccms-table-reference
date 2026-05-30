# `VBKD`

**Description:** Sales Document Business Data — business conditions
**Category:** Standard SAP Table
**References:** 85 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbkd/) — validated 2026-05-30, schema v1.0
**Schema fields:** 104 fields | **Data types:** CHAR(79), CUKY(2), DATS(11), DEC(6), NUMC(4), RAW(1), TIMS(1)

## Key Fields
`GJAHR` | `VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KONDA` | KONDA | T188 | CHAR | 2 | 0 | Price group (customer) |
| `KDGRP` | KDGRP | T151 | CHAR | 2 | 0 | Customer group |
| `BZIRK` | BZIRK | T171 | CHAR | 6 | 0 | Sales district |
| `PLTYP` | PLTYP | T189 | CHAR | 2 | 0 | Price list type |
| `INCO1` | INCO1 | TINC | CHAR | 3 | 0 | Incoterms (Part 1) |
| `INCO2` | INCO2 | — | CHAR | 28 | 0 | Incoterms (Part 2) |
| `KZAZU` | KZAZU_D | — | CHAR | 1 | 0 | Order Combination Indicator |
| `PERFK` | PERFK | TFACD | CHAR | 2 | 0 | Invoice dates (calendar identification) |
| `PERRL` | PERRL | TFACD | CHAR | 2 | 0 | Invoice list schedule (calendar identification) |
| `MRNKZ` | MRNKZ | — | CHAR | 1 | 0 | Manual invoice maintenance |
| `KURRF` | KURRF | — | DEC | 9 | 5 | Exchange rate for FI postings |
| `VALTG` | VALTG | — | NUMC | 2 | 0 | Additional value days |
| `VALDT` | VALDT | — | DATS | 8 | 0 | Fixed value date |
| `ZTERM` | DZTERM | — | CHAR | 4 | 0 | Terms of Payment Key |
| `ZLSCH` | SCHZW_BSEG | T042Z | CHAR | 1 | 0 | Payment Method |
| `KTGRD` | KTGRD | TVKT | CHAR | 2 | 0 | Account assignment group for this customer |
| `KURSK` | KURSK | — | DEC | 9 | 5 | Exchange Rate for Price Determination |
| `PRSDT` | PRSDT | — | DATS | 8 | 0 | Date for pricing and exchange rate |
| `FKDAT` | FKDAT | — | DATS | 8 | 0 | Billing date for billing index and printout |
| `FBUDA` | FBUDA | — | DATS | 8 | 0 | Date on which services rendered |
| `GJAHR` | GJAHR | — | NUMC | 4 | 0 | Fiscal Year |
| `POPER` | POPER | — | NUMC | 3 | 0 | Posting period |
| `STCUR` | STCUR | — | DEC | 9 | 5 | Exchange rate for statistics |
| `MSCHL` | MSCHL | T040 | CHAR | 1 | 0 | Dunning key |
| `MANSP` | MANSP | T040S | CHAR | 1 | 0 | Dunning block |
| `FPLNR` | FPLNR | FPLA | CHAR | 10 | 0 | Billing plan number / invoicing plan number |
| `WAKTION` | WAKTION | WAKH | CHAR | 10 | 0 | Promotion |
| `ABSSC` | ABSSCHE_CM | T691M | CHAR | 6 | 0 | Payment guarantee procedure |
| `LCNUM` | LCNUM | AKKP | CHAR | 10 | 0 | Financial doc. processing: Internal financial doc. number |
| `J_1AFITP` | J_1AFITP_D | J_1AFITP | CHAR | 2 | 0 | Tax type |
| `J_1ARFZ` | J_1ARFZVAT | J_1ARFZ | CHAR | 1 | 0 | Reason for zero VAT |
| `J_1AREGIO` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `J_1AGICD` | J_1AGICD_D | J_1AGICD | CHAR | 2 | 0 | Activity Code for Gross Income Tax |
| `J_1ADTYP` | J_1ADTYP_D | J_1ADTYP | CHAR | 2 | 0 | Distribution Type for Employment Tax |
| `J_1ATXREL` | J_1ATXREL_ | J_1ATXREL | CHAR | 10 | 0 | Tax relevant classification |
| `ABTNR` | ABTNR | TSAB | CHAR | 4 | 0 | Department number |
| `EMPST` | EMPST | — | CHAR | 25 | 0 | Receiving point |
| `BSTKD` | BSTKD | — | CHAR | 35 | 0 | Customer purchase order number |
| `BSTDK` | BSTDK | — | DATS | 8 | 0 | Customer purchase order date |
| `BSARK` | BSARK | T176 | CHAR | 4 | 0 | Customer purchase order type |
| `IHREZ` | IHREZ | — | CHAR | 12 | 0 | Your Reference |
| `BSTKD_E` | BSTKD_E | — | CHAR | 35 | 0 | Ship-to Party&#039;s Purchase Order Number |
| `BSTDK_E` | BSTDK_E | — | DATS | 8 | 0 | Ship-to party&#039;s PO date |
| `BSARK_E` | BSARK_E | T176 | CHAR | 4 | 0 | Ship-to party purchase order type |
| `IHREZ_E` | IHREZ_E | — | CHAR | 12 | 0 | Ship-to party character |
| `POSEX_E` | POSEX_E | — | CHAR | 6 | 0 | Item Number of the Underlying Purchase Order |
| `KURSK_DAT` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `KURRF_DAT` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `KDKG1` | KDKG1 | TVKGG | CHAR | 2 | 0 | Customer condition group 1 |
| `KDKG2` | KDKG2 | TVKGG | CHAR | 2 | 0 | Customer condition group 2 |
| `KDKG3` | KDKG3 | TVKGG | CHAR | 2 | 0 | Customer condition group 3 |
| `KDKG4` | KDKG4 | TVKGG | CHAR | 2 | 0 | Customer condition group 4 |
| `KDKG5` | KDKG5 | TVKGG | CHAR | 2 | 0 | Customer condition group 5 |
| `WKWAE` | WKWAE | TCURC | CUKY | 5 | 0 | Value contract currency |
| `WKKUR` | WKKUR | — | DEC | 9 | 5 | Exchange rate in value contract currency |
| `AKWAE` | AKWAE | TCURC | CUKY | 5 | 0 | Currency key for letter-of-credit procg in foreign trade |
| `AKKUR` | AKKUR | — | DEC | 9 | 5 | Exchange rate for letter-of-credit procg in foreign trade |
| `AKPRZ` | AKPRZ | — | DEC | 5 | 2 | Depreciation percentage for financial document processing |
| `J_1AINDXP` | J_1AINDXP | J_1AINFT20 | CHAR | 5 | 0 | Inflation Index |
| `J_1AIDATEP` | J_1AIDATES | — | DATS | 8 | 0 | Indexing base date |
| `BSTKD_M` | BSTKD_M | — | CHAR | 35 | 0 | Customer PO number as matchcode field |
| `DELCO` | DELCO | TVDC | CHAR | 3 | 0 | Agreed delivery time |
| `FFPRF` | AD01PROFNR | AD01C_PROF | CHAR | 8 | 0 | Dynamic Item Processor Profile |
| `BEMOT` | BEMOT | TBMOT | CHAR | 2 | 0 | Accounting Indicator |
| `FAKTF` | FAKTF | — | CHAR | 2 | 0 | Billing form |
| `RRREL` | RR_RELTYP | — | CHAR | 1 | 0 | Revenue recognition category |
| `ACDATV` | RR_ACDATV | — | CHAR | 1 | 0 | Proposed start date for accrual period |
| `VSART` | VSARTTR | T173 | CHAR | 2 | 0 | Shipping type |
| `TRATY` | TRATY | TVTY | CHAR | 4 | 0 | Means-of-Transport Type |
| `TRMTYP` | TRMTYP | MARA | CHAR | 18 | 0 | Means of Transport |
| `SDABW` | SDABW | TVSAK | CHAR | 4 | 0 | Special processing indicator |
| `WMINR` | WMINR | WWMI | CHAR | 10 | 0 | Product catalog number |
| `FKBER` | FKBER | TFKB | CHAR | 16 | 0 | Functional Area |
| `PODKZ` | PODKZ | — | CHAR | 1 | 0 | Relevant for POD processing |
| `CAMPAIGN` | CGPL_GUID16_R3 | — | RAW | 16 | 0 | Generic project planning: GUID from external R/3 system |
| `VKONT` | CORR_VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `DPBP_REF_FPLNR` | FPLNR | — | CHAR | 10 | 0 | Billing plan number / invoicing plan number |
| `DPBP_REF_FPLTR` | FPLTR | — | NUMC | 6 | 0 | Item for billing plan/invoice plan/payment cards |
| `REVSP` | RR_REVSP | — | CHAR | 1 | 0 | Revenue Distribution Type |
| `REVEVTYP` | RR_REVEVTYP_CUST | — | CHAR | 1 | 0 | Revenue Event Type (Customizing) |
| `VTREF` | CORR_VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `PEROP_BEG` | FM_PEROP_SD_LOW | — | DATS | 8 | 0 | Period of Performance Start Date |
| `PEROP_END` | FM_PEROP_SD_HIGH | — | DATS | 8 | 0 | Period of Performance End Date |
| `STCODE` | J_1ISTCODE | — | CHAR | 3 | 0 | LST CST applicability code |
| `FORMC1` | J_1IFORTYP | — | CHAR | 3 | 0 | Form Type |
| `FORMC2` | J_1IFORTYP | — | CHAR | 3 | 0 | Form Type |
| `STEUC` | STEUC | — | CHAR | 16 | 0 | Control code for consumption taxes in foreign trade |
| `OIC_TIME` | OIC_TIME | — | TIMS | 6 | 0 | Time for time-pricing |
| `OITITLE` | OIC_TITLE | — | CHAR | 1 | 0 | Location of title transfer for Incoterms purposes |
| `OIPTRM1` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM2` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM3` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM4` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM5` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM6` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM7` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM8` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPTRM9` | OIA_PTRM | — | CHAR | 4 | 0 | Payment terms for invoice cycle X |
| `OIPFLIC` | OIH_PFLIC | TPAR | CHAR | 2 | 0 | IS-OIL partner function for tax exemption license |
| `COMPREAS` | CMP_COMPREAS_COPY | — | CHAR | 4 | 0 | Abbreviation for Complaints Reason |
| `MNDID` | SEPA_MNDID | — | CHAR | 35 | 0 | Unique Referene to Mandate per Payment Recipient |
| `PAY_TYPE` | SEPA_PAY_TYPE | — | CHAR | 1 | 0 | SEPA: Transaction Type |
| `SEPON` | SD_SEPA_FLAG | — | CHAR | 1 | 0 | SEPA-Relevance |
| `MNDVG` | SD_SEPA_FLAG | — | CHAR | 1 | 0 | SEPA-Relevance |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABSSC` | VBKD | MANDT | T691M |  | |
| `ABSSC` | VBKD | ABSSC | T691M |  | |
| `ABTNR` | VBKD | MANDT | TSAB |  | |
| `ABTNR` | VBKD | ABTNR | TSAB |  | |
| `AKWAE` | VBKD | AKWAE | TCURC |  | |
| `AKWAE` | VBKD | MANDT | TCURC |  | |
| `BEMOT` | VBKD | MANDT | TBMOT |  | |
| `BEMOT` | VBKD | BEMOT | TBMOT |  | |
| `BSARK` | VBKD | MANDT | T176 |  | |
| `BSARK` | VBKD | BSARK | T176 |  | |
| `BSARK_E` | VBKD | MANDT | T176 |  | |
| `BSARK_E` | VBKD | BSARK_E | T176 |  | |
| `BZIRK` | VBKD | BZIRK | T171 |  | |
| `BZIRK` | VBKD | MANDT | T171 |  | |
| `DELCO` | VBKD | MANDT | TVDC |  | |
| `DELCO` | VBKD | DELCO | TVDC |  | |
| `FFPRF` | VBKD | MANDT | AD01C_PROF |  | |
| `FFPRF` | VBKD | FFPRF | AD01C_PROF |  | |
| `FFPRF` | * |  | AD01C_PROF |  | |
| `FKBER` | VBKD | MANDT | TFKB |  | |
| `FKBER` | VBKD | FKBER | TFKB |  | |
| `FPLNR` | VBKD | FPLNR | FPLA |  | |
| `FPLNR` | VBKD | MANDT | FPLA |  | |
| `INCO1` | VBKD | MANDT | TINC |  | |
| `INCO1` | VBKD | INCO1 | TINC |  | |
| `J_1ADTYP` | VBKD | MANDT | J_1ADTYP |  | |
| `J_1ADTYP` | T001 | BUKRS | J_1ADTYP |  | |
| `J_1ADTYP` | VBKD | J_1ADTYP | J_1ADTYP |  | |
| `J_1AFITP` | &#039;D&#039; |  | J_1AFITP |  | |
| `J_1AFITP` | VBKD | J_1AFITP | J_1AFITP |  | |
| `J_1AFITP` | VBKD | MANDT | J_1AFITP |  | |
| `J_1AGICD` | VBKD | MANDT | J_1AGICD |  | |
| `J_1AGICD` | T001 | LAND1 | J_1AGICD |  | |
| `J_1AGICD` | VBKD | J_1AGICD | J_1AGICD |  | |
| `J_1AINDXP` | VBKD | MANDT | J_1AINFT20 |  | |
| `J_1AINDXP` | VBKD | J_1AINDXP | J_1AINFT20 |  | |
| `J_1AREGIO` | VBKD | J_1AREGIO | T005S |  | |
| `J_1AREGIO` | VBKD | MANDT | T005S |  | |
| `J_1AREGIO` | T001 | LAND1 | T005S |  | |
| `J_1ARFZ` | VBKD | MANDT | J_1ARFZ |  | |
| `J_1ARFZ` | VBKD | J_1ARFZ | J_1ARFZ |  | |
| `J_1ATXREL` | VBKD | MANDT | J_1ATXREL |  | |
| `J_1ATXREL` | VBKD | J_1ATXREL | J_1ATXREL |  | |
| `KDGRP` | VBKD | MANDT | T151 |  | |
| `KDGRP` | VBKD | KDGRP | T151 |  | |
| `KDKG1` | VBKD | KDKG1 | TVKGG |  | |
| `KDKG1` | VBKD | MANDT | TVKGG |  | |
| `KDKG2` | VBKD | MANDT | TVKGG |  | |
| `KDKG2` | VBKD | KDKG2 | TVKGG |  | |
| `KDKG3` | VBKD | MANDT | TVKGG |  | |
| `KDKG3` | VBKD | KDKG3 | TVKGG |  | |
| `KDKG4` | VBKD | MANDT | TVKGG |  | |
| `KDKG4` | VBKD | KDKG4 | TVKGG |  | |
| `KDKG5` | VBKD | MANDT | TVKGG |  | |
| `KDKG5` | VBKD | KDKG5 | TVKGG |  | |
| `KONDA` | VBKD | MANDT | T188 |  | |
| `KONDA` | VBKD | KONDA | T188 |  | |
| `KTGRD` | VBKD | KTGRD | TVKT |  | |
| `KTGRD` | VBKD | MANDT | TVKT |  | |
| `LCNUM` | VBKD | MANDT | AKKP |  | |
| `LCNUM` | VBKD | LCNUM | AKKP |  | |
| `MANDT` | VBKD | MANDT | T000 |  | |
| `MANSP` | VBKD | MANDT | T040S |  | |
| `MANSP` | VBKD | MANSP | T040S |  | |
| `MSCHL` | VBKD | MANDT | T040 |  | |
| `MSCHL` | VBKD | MSCHL | T040 |  | |
| `OIPFLIC` | VBKD | OIPFLIC | TPAR |  | |
| `OIPFLIC` | VBKD | MANDT | TPAR |  | |
| `PERFK` | VBKD | PERFK | TFACD |  | |
| `PERRL` | VBKD | PERRL | TFACD |  | |
| `PLTYP` | VBKD | PLTYP | T189 |  | |
| `PLTYP` | VBKD | MANDT | T189 |  | |
| `POSNR` | VBKD | MANDT | VBUP |  | |
| `POSNR` | VBKD | VBELN | VBUP |  | |
| `POSNR` | VBKD | POSNR | VBUP |  | |
| `SDABW` | VBKD | MANDT | TVSAK |  | |
| `SDABW` | VBKD | SDABW | TVSAK |  | |
| `TRATY` | VBKD | MANDT | TVTY |  | |
| `TRATY` | VBKD | TRATY | TVTY |  | |
| `TRMTYP` | VBKD | MANDT | MARA |  | |
| `TRMTYP` | VBKD | TRMTYP | MARA |  | |
| `VBELN` | VBKD | VBELN | VBUK |  | |
| `VBELN` | VBKD | MANDT | VBUK |  | |
| `VSART` | VBKD | MANDT | T173 |  | |
| `VSART` | VBKD | VSART | T173 |  | |
| `WAKTION` | VBKD | WAKTION | WAKH |  | |
| `WAKTION` | VBKD | MANDT | WAKH |  | |
| `WKWAE` | VBKD | MANDT | TCURC |  | |
| `WKWAE` | VBKD | WKWAE | TCURC |  | |
| `WMINR` | VBKD | MANDT | WWMI |  | |
| `WMINR` | VBKD | WMINR | WWMI |  | |
| `ZLSCH` | VBKD | MANDT | T042Z |  | |
| `ZLSCH` | RV45A | BUKRSL | T042Z |  | |
| `ZLSCH` | VBKD | ZLSCH | T042Z |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `posnr`, `vbeln`, `vkont`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `vkont`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_multi_ecodata_profile.txt`
- `ziscseec_eeus_reb_det.txt`
- `zissd00001.txt`
- `zissd00005.txt`
- `zissd00013.txt`
- `zissd00017.txt`
- `zissd00018.txt`
- `zissd00024.txt`
- `zissd00042.txt`
- `zissd00047.txt`
- `zissd00052.txt`
- `zissd00058.txt`
- `zissd00060.txt`
- `zissd00061.txt`
- `zissd00062.txt`
- `zissd00065.txt`
- `zissd00101.txt`
- `zissd00115.txt`
- `zmmpri000.txt`
- `zsdisqry01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_