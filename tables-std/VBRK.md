# `VBRK`

**Description:** Billing Document Header — billing/invoice header
**Category:** Standard SAP Table
**References:** 32 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbrk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 135 fields | **Data types:** CHAR(113), CUKY(4), CURR(3), DATS(7), DEC(3), NUMC(4), TIMS(1)

## Key Fields
`BELNR` | `GJAHR` | `BUKRS` | `VKONT`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `FKART` | FKART | TVFK | CHAR | 4 | 0 | Billing Type |
| `FKTYP` | FKTYP | — | CHAR | 1 | 0 | Billing category |
| `VBTYP` | VBTYP | — | CHAR | 1 | 0 | SD document category |
| `WAERK` | WAERK | TCURC | CUKY | 5 | 0 | SD Document Currency |
| `VKORG` | VKORG | TVKO | CHAR | 4 | 0 | Sales Organization |
| `VTWEG` | VTWEG | TVTW | CHAR | 2 | 0 | Distribution Channel |
| `KALSM` | KALSMASD | T683 | CHAR | 6 | 0 | Sales and Distribution: Pricing Procedure in Pricing |
| `KNUMV` | KNUMV | — | CHAR | 10 | 0 | Number of the document condition |
| `VSBED` | VSBED | TVSB | CHAR | 2 | 0 | Shipping Conditions |
| `FKDAT` | FKDAT | — | DATS | 8 | 0 | Billing date for billing index and printout |
| `BELNR` | BELNR_D | — | CHAR | 10 | 0 | Accounting Document Number |
| `GJAHR` | GJAHR | — | NUMC | 4 | 0 | Fiscal Year |
| `POPER` | POPER | — | NUMC | 3 | 0 | Posting period |
| `KONDA` | KONDA | T188 | CHAR | 2 | 0 | Price group (customer) |
| `KDGRP` | KDGRP | T151 | CHAR | 2 | 0 | Customer group |
| `BZIRK` | BZIRK | T171 | CHAR | 6 | 0 | Sales district |
| `PLTYP` | PLTYP | T189 | CHAR | 2 | 0 | Price list type |
| `INCO1` | INCO1 | TINC | CHAR | 3 | 0 | Incoterms (Part 1) |
| `INCO2` | INCO2 | — | CHAR | 28 | 0 | Incoterms (Part 2) |
| `EXPKZ` | EXPKZ | — | CHAR | 1 | 0 | Export indicator |
| `RFBSK` | RFBSK | — | CHAR | 1 | 0 | Status for transfer to accounting |
| `MRNKZ` | MRNKZ | — | CHAR | 1 | 0 | Manual invoice maintenance |
| `KURRF` | KURRF | — | DEC | 9 | 5 | Exchange rate for FI postings |
| `CPKUR` | CPKUR | — | CHAR | 1 | 0 | ID:Exchange rate setting (no new rate determ.in bill.doc.) |
| `VALTG` | VALTG | — | NUMC | 2 | 0 | Additional value days |
| `VALDT` | VALDT | — | DATS | 8 | 0 | Fixed value date |
| `ZTERM` | DZTERM | — | CHAR | 4 | 0 | Terms of Payment Key |
| `ZLSCH` | SCHZW_BSEG | T042Z | CHAR | 1 | 0 | Payment Method |
| `KTGRD` | KTGRD | TVKT | CHAR | 2 | 0 | Account assignment group for this customer |
| `LAND1` | LLAND | T005 | CHAR | 3 | 0 | Country of Destination |
| `REGIO` | REGIO | T005S | CHAR | 3 | 0 | Region (State, Province, County) |
| `COUNC` | COUNC | T005E | CHAR | 3 | 0 | County Code |
| `CITYC` | CITYC | T005G | CHAR | 4 | 0 | City Code |
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `TAXK1` | TAXK1 | — | CHAR | 1 | 0 | Tax classification 1 for customer |
| `TAXK2` | TAXK2 | — | CHAR | 1 | 0 | Tax classification 2 for customer |
| `TAXK3` | TAXK3 | — | CHAR | 1 | 0 | Tax classification 3 for customer |
| `TAXK4` | TAXK4 | — | CHAR | 1 | 0 | Tax Classification 4 Customer |
| `TAXK5` | TAXK5 | — | CHAR | 1 | 0 | Tax classification 5 for customer |
| `TAXK6` | TAXK6 | — | CHAR | 1 | 0 | Tax classification 6 for customer |
| `TAXK7` | TAXK7 | — | CHAR | 1 | 0 | Tax classification 7 for customer |
| `TAXK8` | TAXK8 | — | CHAR | 1 | 0 | Tax classification 8 for customer |
| `TAXK9` | TAXK9 | — | CHAR | 1 | 0 | Tax classification 9 for customer |
| `NETWR` | NETWR | — | CURR | 15 | 2 | Net Value in Document Currency |
| `ZUKRI` | DZUKRI | — | CHAR | 40 | 0 | Combination criteria in the billing document |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `ERZET` | ERZET | — | TIMS | 6 | 0 | Entry time |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `STAFO` | STAFO | — | CHAR | 6 | 0 | Update group for statistics update |
| `KUNRG` | KUNRG | KNA1 | CHAR | 10 | 0 | Payer |
| `KUNAG` | KUNAG | KNA1 | CHAR | 10 | 0 | Sold-to party |
| `MABER` | MABER | T047M | CHAR | 2 | 0 | Dunning Area |
| `STWAE` | STWAE | TCURC | CUKY | 5 | 0 | Statistics currency |
| `EXNUM` | EXNUM | EIKP | CHAR | 10 | 0 | Number of foreign trade data in MM and SD documents |
| `STCEG` | STCEG | — | CHAR | 20 | 0 | VAT Registration Number |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `SFAKN` | SFAKN | VBUK | CHAR | 10 | 0 | Cancelled billing document number |
| `KNUMA` | KNUMA | KONA | CHAR | 10 | 0 | Agreement (various conditions grouped together) |
| `FKART_RL` | FKART_RL | TVFK | CHAR | 4 | 0 | Invoice list type |
| `FKDAT_RL` | FKDAT_RL | — | DATS | 8 | 0 | Billing date for the invoice list |
| `KURST` | KURST | TCURV | CHAR | 4 | 0 | Exchange Rate Type |
| `MSCHL` | MSCHL | T040 | CHAR | 1 | 0 | Dunning key |
| `MANSP` | MANSP | T040S | CHAR | 1 | 0 | Dunning block |
| `SPART` | SPART | TSPA | CHAR | 2 | 0 | Division |
| `KKBER` | KKBER | T014 | CHAR | 4 | 0 | Credit control area |
| `KNKLI` | KNKLI | KNA1 | CHAR | 10 | 0 | Customer&#039;s account number with credit limit reference |
| `CMWAE` | WAERS_CM | TCURC | CUKY | 5 | 0 | Currency key of credit control area |
| `CMKUF` | CMKUF | — | DEC | 9 | 5 | Credit data exchange rate at billing document rate |
| `HITYP_PR` | HITYP_PR | THIT | CHAR | 1 | 0 | Hierarchy type for pricing |
| `BSTNK_VF` | BSTKD | — | CHAR | 35 | 0 | Customer purchase order number |
| `VBUND` | RASSC | T880 | CHAR | 6 | 0 | Company ID of trading partner |
| `FKART_AB` | FKART_AB | — | CHAR | 4 | 0 | Accrual billing type |
| `KAPPL` | KAPPL | — | CHAR | 2 | 0 | Application |
| `LANDTX` | LANDTX | — | CHAR | 3 | 0 | Tax departure country |
| `STCEG_H` | STCEG_H | — | CHAR | 1 | 0 | Origin of sales tax ID number |
| `STCEG_L` | STCEG_L | — | CHAR | 3 | 0 | Country of Sales Tax ID Number |
| `XBLNR` | XBLNR_V1 | — | CHAR | 16 | 0 | Reference Document Number |
| `ZUONR` | ORDNR_V | — | CHAR | 18 | 0 | Assignment number |
| `MWSBK` | MWSBP | — | CURR | 13 | 2 | Tax amount in document currency |
| `LOGSYS` | LOGSYS | — | CHAR | 10 | 0 | Logical system |
| `FKSTO` | FKSTO | — | CHAR | 1 | 0 | Billing document is cancelled |
| `XEGDR` | XEGDR | — | CHAR | 1 | 0 | Indicator: Triangular deal within the EU ? |
| `RPLNR` | RPLNR | FPLA | CHAR | 10 | 0 | Number of payment card plan type |
| `LCNUM` | LCNUM | AKKP | CHAR | 10 | 0 | Financial doc. processing: Internal financial doc. number |
| `J_1AFITP` | J_1AFITP_D | J_1AFITP | CHAR | 2 | 0 | Tax type |
| `KURRF_DAT` | WWERT_D | — | DATS | 8 | 0 | Translation Date |
| `AKWAE` | AKWAE | TCURC | CUKY | 5 | 0 | Currency key for letter-of-credit procg in foreign trade |
| `AKKUR` | AKKUR | — | DEC | 9 | 5 | Exchange rate for letter-of-credit procg in foreign trade |
| `KIDNO` | KIDNO | — | CHAR | 30 | 0 | Payment Reference |
| `BVTYP` | BVTYP | — | CHAR | 4 | 0 | Partner Bank Type |
| `NUMPG` | J_1ANOPG | — | NUMC | 3 | 0 | Number of pages of invoice |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `VKONT` | CORR_VKONT_KK | — | CHAR | 12 | 0 | Contract Account Number |
| `FKK_DOCSTAT` | DOCSTAT_KK | — | CHAR | 1 | 0 | Additional Status Transfer to Fin. Accounting (Res. RFBSK) |
| `NRZAS` | CHAR12 | — | CHAR | 12 | 0 | Character Field of Length 12 |
| `SPE_BILLING_IND` | /SPE/DE_BILLING_IND | — | CHAR | 1 | 0 | EWM Billing Indicator |
| `VTREF` | CORR_VTREF_KK | — | CHAR | 20 | 0 | Reference Specifications from Contract |
| `FK_SOURCE_SYS` | FK_SOURCE_SYS | — | CHAR | 10 | 0 | Source System |
| `FKTYP_CRM` | FKTYP_CRM | — | CHAR | 1 | 0 | Billing Category in CRM |
| `STGRD` | STGRD | T041C | CHAR | 2 | 0 | Reason for Reversal |
| `VBTYP_EXT` | TDD_VBTYP_EXT | — | CHAR | 4 | 0 | Extension of SD Document Category |
| `DPC_REL` | /SAPPCE/DPC_REL | — | CHAR | 1 | 0 | Flag: DPC relevant |
| `OICHEADOFF` | KNRZE | — | CHAR | 10 | 0 | Head office account number (in branch accounts) |
| `OIC_INPD` | OIC_INPD | — | CHAR | 1 | 0 | Invoice pricing date rule |
| `OINETCYC` | OIA_NETCYC | T008 | CHAR | 1 | 0 | Netting cycle (FI blocking indicator) |
| `OIEXGNUM` | OIA_EXGNUM | — | CHAR | 10 | 0 | Exchange agreement number |
| `OIEXGTYP` | OIA_EXGTYP | — | CHAR | 4 | 0 | Exchange type |
| `OIFEEPD` | OIA_FEEPD | — | CHAR | 1 | 0 | Fee pricing date |
| `OIRIINVDOC` | OIRI_INVDOC | — | CHAR | 3 | 0 | SSR invoicing -  invoicing document type |
| `OIRIPBLNR` | OIF_PBLNR | — | CHAR | 10 | 0 | Business location identifier (IS-Oil MRN) |
| `OIRICOMMCAL` | OIRI_COMMCAL | — | CHAR | 2 | 0 | Calendar for monthly commission recalculation |
| `OIRIDCLAIM` | OIRI_DCLAIM | — | CHAR | 1 | 0 | Daily claim document |
| `OIRIPCTOT` | OIRI_PCTOT | — | CURR | 15 | 2 | Payment card total |
| `OIRICHIND` | OIRI_CHIND | — | CHAR | 1 | 0 | Clearing house document indicator |
| `OIRMATHANDGRP` | OIRA_MATHANDGRP | — | CHAR | 2 | 0 | Material handling group (IS-Oil SSR) |
| `OIR_CHOBJ` | OIRE_CHOBJ | — | CHAR | 6 | 0 | SSR PC: Clearing house |
| `OICSDPORGINV` | OIC_VBELN_ORG | — | CHAR | 10 | 0 | Original billing document |
| `OICSDPVERNO` | OIC_SDP_DVERNO | — | CHAR | 2 | 0 | Version number sequence |
| `OIU_DN_NO` | — | — | CHAR | 20 | 0 | OIU_DN_NO |
| `OIU_WL_NO` | — | — | CHAR | 15 | 0 | OIU_WL_NO |
| `OIU_WC_NO` | — | — | CHAR | 5 | 0 | OIU_WC_NO |
| `OIU_MP_NO` | — | — | CHAR | 20 | 0 | OIU_MP_NO |
| `OIU_MAJPD_CD` | — | — | CHAR | 1 | 0 | OIU_MAJPD_CD |
| `OIU_VNAME` | — | — | CHAR | 6 | 0 | OIU_VNAME |
| `OIU_DOI_NO` | — | — | CHAR | 5 | 0 | OIU_DOI_NO |
| `OIU_VBELN` | — | — | CHAR | 10 | 0 | OIU_VBELN |
| `OIU_PPA_RSN_CD` | — | — | CHAR | 2 | 0 | OIU_PPA_RSN_CD |
| `OIU_PRCS_DT` | — | — | DATS | 8 | 0 | OIU_PRCS_DT |
| `OIU_FREQ_CD` | — | — | CHAR | 1 | 0 | OIU_FREQ_CD |
| `MNDID` | SEPA_MNDID | — | CHAR | 35 | 0 | Unique Referene to Mandate per Payment Recipient |
| `PAY_TYPE` | SEPA_PAY_TYPE | — | CHAR | 1 | 0 | SEPA: Transaction Type |
| `SEPON` | SD_SEPA_FLAG | — | CHAR | 1 | 0 | SEPA-Relevance |
| `MNDVG` | SD_SEPA_FLAG | — | CHAR | 1 | 0 | SEPA-Relevance |
| `SPPAYM` | SPPAYM | — | CHAR | 2 | 0 | Payment Form for Special Payment Method |
| `SPPORD` | SPPORD | — | CHAR | 10 | 0 | Sales Order for Special Payment Method |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AKWAE` | VBRK | MANDT | TCURC |  | |
| `AKWAE` | VBRK | AKWAE | TCURC |  | |
| `BUKRS` | VBRK | BUKRS | T001 |  | |
| `BUKRS` | VBRK | MANDT | T001 |  | |
| `BUPLA` | VBRK | BUPLA | J_1BBRANCH |  | |
| `BUPLA` | VBRK | MANDT | J_1BBRANCH |  | |
| `BUPLA` | VBRK | BUKRS | J_1BBRANCH |  | |
| `BZIRK` | VBRK | MANDT | T171 |  | |
| `BZIRK` | VBRK | BZIRK | T171 |  | |
| `CITYC` | VBRK | CITYC | T005G |  | |
| `CITYC` | VBRK | MANDT | T005G |  | |
| `CITYC` | VBRK | LAND1 | T005G |  | |
| `CITYC` | VBRK | REGIO | T005G |  | |
| `CMWAE` | VBRK | MANDT | TCURC |  | |
| `CMWAE` | VBRK | CMWAE | TCURC |  | |
| `COUNC` | VBRK | REGIO | T005E |  | |
| `COUNC` | VBRK | COUNC | T005E |  | |
| `COUNC` | VBRK | MANDT | T005E |  | |
| `COUNC` | VBRK | LAND1 | T005E |  | |
| `EXNUM` | VBRK | MANDT | EIKP |  | |
| `EXNUM` | VBRK | EXNUM | EIKP |  | |
| `FKART` | VBRK | MANDT | TVFK |  | |
| `FKART` | VBRK | FKART | TVFK |  | |
| `FKART_RL` | VBRK | MANDT | TVFK |  | |
| `FKART_RL` | VBRK | FKART_RL | TVFK |  | |
| `HITYP_PR` | VBRK | MANDT | THIT |  | |
| `HITYP_PR` | VBRK | HITYP_PR | THIT |  | |
| `INCO1` | VBRK | MANDT | TINC |  | |
| `INCO1` | VBRK | INCO1 | TINC |  | |
| `J_1AFITP` | SY | MANDT | J_1AFITP |  | |
| `J_1AFITP` | &#039;D&#039; |  | J_1AFITP |  | |
| `J_1AFITP` | VBRK | J_1AFITP | J_1AFITP |  | |
| `KALSM` | VBRK | MANDT | T683 |  | |
| `KALSM` | T681Z | KVEWE | T683 |  | |
| `KALSM` | T681Z | KAPPL | T683 |  | |
| `KALSM` | VBRK | KALSM | T683 |  | |
| `KDGRP` | VBRK | MANDT | T151 |  | |
| `KDGRP` | VBRK | KDGRP | T151 |  | |
| `KKBER` | VBRK | MANDT | T014 |  | |
| `KKBER` | VBRK | KKBER | T014 |  | |
| `KNKLI` | VBRK | MANDT | KNA1 |  | |
| `KNKLI` | VBRK | KNKLI | KNA1 |  | |
| `KNUMA` | VBRK | MANDT | KONA |  | |
| `KNUMA` | VBRK | KNUMA | KONA |  | |
| `KONDA` | VBRK | MANDT | T188 |  | |
| `KONDA` | VBRK | KONDA | T188 |  | |
| `KTGRD` | VBRK | MANDT | TVKT |  | |
| `KTGRD` | VBRK | KTGRD | TVKT |  | |
| `KUNAG` | VBRK | MANDT | KNA1 |  | |
| `KUNAG` | VBRK | KUNAG | KNA1 |  | |
| `KUNRG` | VBRK | MANDT | KNA1 |  | |
| `KUNRG` | VBRK | KUNRG | KNA1 |  | |
| `KURST` | VBRK | KURST | TCURV |  | |
| `KURST` | VBRK | MANDT | TCURV |  | |
| `LAND1` | VBRK | MANDT | T005 |  | |
| `LAND1` | VBRK | LAND1 | T005 |  | |
| `LCNUM` | VBRK | MANDT | AKKP |  | |
| `LCNUM` | VBRK | LCNUM | AKKP |  | |
| `MABER` | VBRK | MANDT | T047M |  | |
| `MABER` | VBRK | BUKRS | T047M |  | |
| `MABER` | VBRK | MABER | T047M |  | |
| `MANDT` | VBRK | MANDT | T000 |  | |
| `MANSP` | VBRK | MANSP | T040S |  | |
| `MANSP` | VBRK | MANDT | T040S |  | |
| `MSCHL` | VBRK | MANDT | T040 |  | |
| `MSCHL` | VBRK | MSCHL | T040 |  | |
| `OINETCYC` | VBRK | MANDT | T008 |  | |
| `OINETCYC` | VBRK | OINETCYC | T008 |  | |
| `PLTYP` | VBRK | PLTYP | T189 |  | |
| `PLTYP` | VBRK | MANDT | T189 |  | |
| `REGIO` | VBRK | MANDT | T005S |  | |
| `REGIO` | VBRK | LAND1 | T005S |  | |
| `REGIO` | VBRK | REGIO | T005S |  | |
| `RPLNR` | VBRK | MANDT | FPLA |  | |
| `RPLNR` | VBRK | RPLNR | FPLA |  | |
| `SFAKN` | VBRK | MANDT | VBUK |  | |
| `SFAKN` | VBRK | SFAKN | VBUK |  | |
| `SPART` | VBRK | MANDT | TSPA |  | |
| `SPART` | VBRK | SPART | TSPA |  | |
| `STGRD` | VBRK | MANDT | T041C |  | |
| `STGRD` | VBRK | STGRD | T041C |  | |
| `STWAE` | VBRK | MANDT | TCURC |  | |
| `STWAE` | VBRK | STWAE | TCURC |  | |
| `VBELN` | VBRK | MANDT | VBUK |  | |
| `VBELN` | VBRK | VBELN | VBUK |  | |
| `VBUND` | VBRK | MANDT | T880 |  | |
| `VBUND` | VBRK | VBUND | T880 |  | |
| `VKORG` | VBRK | MANDT | TVKO |  | |
| `VKORG` | VBRK | VKORG | TVKO |  | |
| `VSBED` | VBRK | VSBED | TVSB |  | |
| `VSBED` | VBRK | MANDT | TVSB |  | |
| `VTWEG` | VBRK | MANDT | TVTW |  | |
| `VTWEG` | VBRK | VTWEG | TVTW |  | |
| `WAERK` | VBRK | MANDT | TCURC |  | |
| `WAERK` | VBRK | WAERK | TCURC |  | |
| `ZLSCH` | VBRK | ZLSCH | T042Z |  | |
| `ZLSCH` | VBRK | MANDT | T042Z |  | |
| `ZLSCH` | T001 | LAND1 | T042Z |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `aedat`, `erdat`, `fkart`, `fkdat`, `fksto`, `fktyp`, `kunag`, `rfbsk`, `sfakn`, `vbeln`, `vbtyp`, `vkont`, `vkorg`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `erdat`, `fkdat`, `vbtyp`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisbi0013.txt`
- `ziscs0040.txt`
- `zissd00002.txt`
- `zissd00004.txt`
- `zissd00006.txt`
- `zissd00007.txt`
- `zissd00011.txt`
- `zissd00012.txt`
- `zissd00016.txt`
- `zissd00023.txt`
- `zissd00045.txt`
- `zissd00048.txt`
- `zissd00050.txt`
- `zissd00054.txt`
- `zissd00063.txt`
- `zissd00065.txt`
- `zmmpri000.txt`
- `zsdisqry02.txt`
- `zsdslcrm01.txt`
- `zsdsodl05.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_