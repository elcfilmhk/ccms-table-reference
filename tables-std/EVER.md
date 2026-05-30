# `EVER`

**Description:** Contract — master contract between customer and utility
**Category:** Standard SAP Table
**References:** 1628 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/ever/) — validated 2026-05-30, schema v1.0
**Schema fields:** 92 fields | **Data types:** CHAR(70), DATS(13), NUMC(8), TIMS(1)

## Key Fields
`BUKRS` | `AUFNR` | `ANLAGE` | `VKONTO`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `BUKRS` | BUKRS | T001 | CHAR | 4 | 0 | Company Code |
| `SPARTE` | SPARTE | TESPT | CHAR | 2 | 0 | Division |
| `EIGENVERBR` | EIGENVERBR | — | CHAR | 1 | 0 | Plant or company consumption |
| `KOFIZ` | E_KOFIZ | TE097 | CHAR | 2 | 0 | Account determination ID for IS-U contracts |
| `PORTION` | PORTIONABW | TE420 | CHAR | 8 | 0 | Alternative portion |
| `ABSLANFO` | ABSLANFO | — | CHAR | 1 | 0 | Budget billing request for debtor |
| `ABSZYK` | ABSZYKV | — | CHAR | 2 | 0 | Overrriding BB cycle on contract level |
| `ABSMNANP` | ABSMNANP | — | CHAR | 1 | 0 | Do not adjust budget billing amount automatically |
| `GEMFAKT` | E_GEMFAKT | — | CHAR | 1 | 0 | Invoice Contracts Jointly (Mandatory Contracts) |
| `MANABR` | MANABR | — | CHAR | 1 | 0 | Bill contract manually |
| `ABRSPERR` | ABRSPERR | TE021 | CHAR | 2 | 0 | Reason for blocking billing |
| `ABRFREIG` | ABRFREIG | TE023 | CHAR | 2 | 0 | Reason for releasing billing |
| `BSTATUS` | BEARKZ | TE643 | CHAR | 2 | 0 | Processing status |
| `KOSTL` | KOSTL | CSKS | CHAR | 10 | 0 | Cost Center |
| `VBEZ` | E_VBEZ | — | CHAR | 35 | 0 | Text for contract |
| `VBEGINN` | E_VBEGINN | — | DATS | 8 | 0 | Start of contract |
| `EINZDAT_ALT` | EINZDAT_ALT | — | DATS | 8 | 0 | Move-in date from legacy system |
| `VENDE` | E_VENDE | — | DATS | 8 | 0 | End of contract |
| `KUENDDAT` | KUENDAT | — | DATS | 8 | 0 | Cancellation date of contract |
| `KFRIST` | KUENZEIT | — | NUMC | 3 | 0 | Number of time units for cancellation |
| `KUENPER` | KUENPER | — | CHAR | 1 | 0 | Time unit for cancellation |
| `VBISDAT` | E_VBISDAT | — | DATS | 8 | 0 | Renewal date of contract |
| `VERLAENG` | VERZEIT | — | NUMC | 3 | 0 | Number of time units for renewal |
| `VERPER` | VERPER | — | CHAR | 1 | 0 | Time unit for renewal |
| `VABSCHLEVU` | E_VSCHLEVU | — | DATS | 8 | 0 | Date on which utility concluded the contract |
| `VABSCHLKND` | E_VSCHLKND | — | DATS | 8 | 0 | Date on which customer concluded the contract |
| `VABSCHLKNDTI` | E_VSCHLKNDTI | — | TIMS | 6 | 0 | Time at which customer signed contract |
| `PERSNR` | PERNR_D | — | NUMC | 8 | 0 | Personnel Number |
| `VREFER` | E_VREFER | — | CHAR | 20 | 0 | Contract number from legacy system |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `BEGRU` | BEGRU | — | CHAR | 4 | 0 | Authorization Group |
| `LOEVM` | LOEVM | — | CHAR | 1 | 0 | Deletion Indicator |
| `TXJCD` | TXJCD | — | CHAR | 15 | 0 | Tax Jurisdiction |
| `MANOUTSORT` | MANOUTSORT | TE127 | CHAR | 8 | 0 | Reason for manual outsorting in billing |
| `FAKTURIERT` | FAKTURIERT | — | CHAR | 1 | 0 | Contract has already been invoiced |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `PS_PSP_PNR` | PS_PSP_PNR | PRPS | NUMC | 8 | 0 | Work Breakdown Structure Element (WBS Element) |
| `PRCTR` | PRCTR | CEPC | CHAR | 10 | 0 | Profit Center |
| `COPAKONT` | E_COPAKONT | — | CHAR | 1 | 0 | Indicator: Profitability segment assigned (CO-PA) |
| `AUSGRUP` | AUSGRUP | TE191 | CHAR | 8 | 0 | Outsorting check group for billing |
| `OUTCOUNT` | OUTCOUNT | — | NUMC | 2 | 0 | Number of manual outsortings to be carried out yet |
| `PYPLT` | E_PYPLT | TE015 | CHAR | 4 | 0 | Payment plan type |
| `PYPLS` | E_PYPLS | — | NUMC | 2 | 0 | Starting month of payment plan |
| `GSBER` | GSBER | TGSB | CHAR | 4 | 0 | Business Area |
| `SEGMENT` | SEGMT_KK | FAGL_SEGM | CHAR | 10 | 0 | Segment for Segmental Reporting |
| `SERVICEID` | SERVICE_PROV | ESERVPROV | CHAR | 10 | 0 | Service Provider |
| `SRVPRVREF` | SRVPRVREF | — | CHAR | 30 | 0 | Reference number of service provider |
| `BILLMETHOD` | BILLMETHOD | — | CHAR | 2 | 0 | Billing method |
| `STAGRUVER` | E_STGRUV | TE770 | CHAR | 2 | 0 | Statistics group for contract |
| `PYPLA` | E_PYPLA | — | NUMC | 2 | 0 | Alternative start month of payment plan |
| `BILLFINIT` | BILLFINIT | — | CHAR | 1 | 0 | Contract terminated for billing reasons |
| `BFA_DEB_STAT` | E_BFA_PROC_DEBIT | — | CHAR | 1 | 0 | Payment plan - BF amount not released for receivable |
| `BFA_CRED_STAT` | E_BFA_PROC_CREDIT | — | CHAR | 1 | 0 | Payment plan - BF amount not released for credit |
| `SALESEMPLOYEE` | VRTNR | — | NUMC | 8 | 0 | Sales employee |
| `SALESPARTNER` | ESALESPARTNER | KNA1 | CHAR | 10 | 0 | Sales partners |
| `SALESDOCUMENT` | VBELN | VBUK | CHAR | 10 | 0 | Sales and Distribution Document Number |
| `PS_STARTDAT` | PS_STARTDAT | — | DATS | 8 | 0 | Start Date of Payment Scheme (PS) |
| `SERVPROV_PAY` | SERVPROV_PAY | ESERVPROV_PAY | CHAR | 4 | 0 | Payment Class |
| `INVOICING_PARTY` | INVOICING_PARTY | — | CHAR | 10 | 0 | Service Provider That Invoices the Contract |
| `COKEY` | COKEY_EE2 | TECOK | CHAR | 10 | 0 | CO account assignment key, IS-U contract |
| `BUPLA` | BUPLA | J_1BBRANCH | CHAR | 4 | 0 | Business Place |
| `CONTRACTCLASS` | CONTRACTCLASS | TECONTRACTCLASS | CHAR | 4 | 0 | Contract Class |
| `CANCREASON` | VKGRU_VEDA | — | CHAR | 2 | 0 | Reason for Cancellation of Contract |
| `CANCREASON_NEW` | ECRMT_SRV_CANCEL_REASON | — | CHAR | 4 | 0 | Cancellation Reason (CRM) |
| `EXTRAPOLWASTE` | EXTRAPOLWASTE | — | CHAR | 2 | 0 | Category of Waste Disposal Budget Billing Extrapolation |
| `PPM_CONTRACT` | E_PP_PPM_CONTRACT | — | CHAR | 1 | 0 | Identifies Contract as Prepayment Meter Contract |
| `OSB_GROUP` | E_OSB_GROUP | TE555 | CHAR | 3 | 0 | On-Site Billing Group |
| `OUCONT` | OUCONT | — | CHAR | 1 | 0 | Outline Contract |
| `RULEGR` | RULEGR | — | CHAR | 10 | 0 | Rule Group for Outline Agreements |
| `REGIOGROUP` | REGIOGROUP | ADRREGGRP | CHAR | 8 | 0 | Regional structure grouping |
| `CMGRP` | CMGRP_CM_KK | TFK041B | CHAR | 2 | 0 | Collection Management: Master Data Group |
| `STRAT` | STRAT_CM_KK | TFK047X | CHAR | 2 | 0 | Collection Strategy |
| `CPERS` | CPERS_CM_KK | — | CHAR | 10 | 0 | Collections Contact Person |
| `ANLAGE` | ANLAGE | — | CHAR | 10 | 0 | Installation |
| `VKONTO` | VKONT_KK | FKKVK | CHAR | 12 | 0 | Contract Account Number |
| `KZSONDEINZ` | KZSONDEINZ | — | CHAR | 1 | 0 | Move-In Processing (Special Case) |
| `KZSONDAUSZ` | KZSONDAUSZ | — | CHAR | 1 | 0 | Special move-out processing case exists |
| `AUTEIGEINZ` | AUTEIGEINZ | — | CHAR | 1 | 0 | Automatic Owner Move-In |
| `EINZDAT` | EINZDAT | — | DATS | 8 | 0 | Move-In Date |
| `AUSZDAT` | AUSZDAT | — | DATS | 8 | 0 | Move-Out Date |
| `ABSSTOPDAT` | ABSSTOPDAT | — | DATS | 8 | 0 | Stop date for budget bill. requests in the case of move-out |
| `SCHLFAKT` | SCHLFAKT | — | CHAR | 1 | 0 | Joint final billing for move-in/out |
| `MAHNV` | MAHNV_KK | TFK047A | CHAR | 2 | 0 | Dunning Procedure |
| `MAHNVUMZ` | MAHNV_UMZ | TFK047A | CHAR | 2 | 0 | Move-in/out dunning procedure |
| `MANSP` | MANSP_KK | TFK047S | CHAR | 1 | 0 | Dunning Lock Reason |
| `BEZUG` | BEZUG | — | CHAR | 1 | 0 | Reference |
| `TRANSVER` | E_TRANSVER | EVER | CHAR | 10 | 0 | Transfer contract |
| `SSWTCREASON` | SSWTCREASON | TE960 | CHAR | 2 | 0 | Reasons for contract change |
| `XVERA` | XVERA | — | CHAR | 1 | 0 | Contract created due to data transfer |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABRFREIG` | EVER | MANDT | TE023 |  | |
| `ABRFREIG` | EVER | ABRFREIG | TE023 |  | |
| `ABRSPERR` | EVER | MANDT | TE021 |  | |
| `ABRSPERR` | EVER | ABRSPERR | TE021 |  | |
| `AUFNR` | EVER | MANDT | AUFK |  | |
| `AUFNR` | EVER | AUFNR | AUFK |  | |
| `AUSGRUP` | EVER | MANDT | TE191 |  | |
| `AUSGRUP` | EVER | AUSGRUP | TE191 |  | |
| `BSTATUS` | EVER | MANDT | TE643 |  | |
| `BSTATUS` | EVER | BSTATUS | TE643 |  | |
| `BUKRS` | EVER | MANDT | T001 |  | |
| `BUKRS` | EVER | BUKRS | T001 |  | |
| `BUPLA` | SYST | MANDT | J_1BBRANCH |  | |
| `BUPLA` | EVER | BUKRS | J_1BBRANCH |  | |
| `BUPLA` | EVER | BUPLA | J_1BBRANCH |  | |
| `CMGRP` | SYST | MANDT | TFK041B |  | |
| `CMGRP` | EVER | CMGRP | TFK041B |  | |
| `COKEY` | SYST | MANDT | TECOK |  | |
| `COKEY` | EVER | COKEY | TECOK |  | |
| `CONTRACTCLASS` | EVER | CONTRACTCLASS | TECONTRACTCLASS |  | |
| `CONTRACTCLASS` | SYST | MANDT | TECONTRACTCLASS |  | |
| `GSBER` | EVER | MANDT | TGSB |  | |
| `GSBER` | EVER | GSBER | TGSB |  | |
| `KOFIZ` | EVER | MANDT | TE097 |  | |
| `KOFIZ` | EVER | BUKRS | TE097 |  | |
| `KOFIZ` | EVER | SPARTE | TE097 |  | |
| `KOFIZ` | EVER | KOFIZ | TE097 |  | |
| `KOSTL` | * |  | CSKS |  | |
| `KOSTL` | EVER | MANDT | CSKS |  | |
| `KOSTL` | * |  | CSKS |  | |
| `KOSTL` | EVER | KOSTL | CSKS |  | |
| `MAHNV` | EVER | MANDT | TFK047A |  | |
| `MAHNV` | EVER | MAHNV | TFK047A |  | |
| `MAHNVUMZ` | SYST | MANDT | TFK047A |  | |
| `MAHNVUMZ` | EVER | MAHNVUMZ | TFK047A |  | |
| `MANDT` | EVER | MANDT | T000 |  | |
| `MANOUTSORT` | EVER | MANOUTSORT | TE127 |  | |
| `MANOUTSORT` | EVER | MANDT | TE127 |  | |
| `MANSP` | EVER | MANDT | TFK047S |  | |
| `MANSP` | EVER | MANSP | TFK047S |  | |
| `OSB_GROUP` | SYST | MANDT | TE555 |  | |
| `OSB_GROUP` | EVER | OSB_GROUP | TE555 |  | |
| `PORTION` | EVER | MANDT | TE420 |  | |
| `PORTION` | EVER | PORTION | TE420 |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | * |  | CEPC |  | |
| `PRCTR` | EVER | MANDT | CEPC |  | |
| `PRCTR` | EVER | PRCTR | CEPC |  | |
| `PS_PSP_PNR` | EVER | MANDT | PRPS |  | |
| `PS_PSP_PNR` | EVER | PS_PSP_PNR | PRPS |  | |
| `PYPLT` | EVER | MANDT | TE015 |  | |
| `PYPLT` | EVER | PYPLT | TE015 |  | |
| `REGIOGROUP` | EVER | MANDT | ADRREGGRP |  | |
| `REGIOGROUP` | EVER | REGIOGROUP | ADRREGGRP |  | |
| `SALESDOCUMENT` | EVER | SALESDOCUMENT | VBUK |  | |
| `SALESDOCUMENT` | SYST | MANDT | VBUK |  | |
| `SALESPARTNER` | SYST | MANDT | KNA1 |  | |
| `SALESPARTNER` | EVER | SALESPARTNER | KNA1 |  | |
| `SEGMENT` | SYST | MANDT | FAGL_SEGM |  | |
| `SEGMENT` | EVER | SEGMENT | FAGL_SEGM |  | |
| `SERVICEID` | SYST | MANDT | ESERVPROV |  | |
| `SERVICEID` | EVER | SERVICEID | ESERVPROV |  | |
| `SERVPROV_PAY` | SYST | MANDT | ESERVPROV_PAY |  | |
| `SERVPROV_PAY` | EVER | SERVPROV_PAY | ESERVPROV_PAY |  | |
| `SPARTE` | EVER | MANDT | TESPT |  | |
| `SPARTE` | EVER | SPARTE | TESPT |  | |
| `SSWTCREASON` | SYST | MANDT | TE960 |  | |
| `SSWTCREASON` | EVER | SSWTCREASON | TE960 |  | |
| `STAGRUVER` | EVER | MANDT | TE770 |  | |
| `STAGRUVER` | EVER | STAGRUVER | TE770 |  | |
| `STRAT` | SYST | MANDT | TFK047X |  | |
| `STRAT` | EVER | STRAT | TFK047X |  | |
| `TRANSVER` | EVER | MANDT | EVER |  | |
| `TRANSVER` | EVER | TRANSVER | EVER |  | |
| `VKONTO` | EVER | MANDT | FKKVK |  | |
| `VKONTO` | EVER | VKONTO | FKKVK |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ANL`, `ANLAGE`, `AUSZDAT`, `EINZDAT`, `EINZDAT_ALT`, `LOEVM`, `STAGRUVER`, `VERTRAG`, `VKO`, `VKONTO`, `ZZFIXDATE`, `abrsperr`, `aedat`, `anlage`, `auszdat`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `AUSZDAT`, `LOEVM`, `VERTRAG`, `VKONTO`, `anlage`, `auszdat`, `erdat`, `loevm`, `stagruver`, `vertrag`, `vkonto`

## Join Paths
- `EVER.VKONTO` → `FKKVKP.VKONT` — Contract → CA
- `EVER.ANLAGE` → `EANL.ANLAGE` — Contract → Installation

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_iscs_wis_prem_info.txt`
- `z_isdm_mol_map_fc_loc.txt`
- `zisbi0033.txt`
- `zisbi0119.txt`
- `zisbi0219f01.txt`
- `ziscs0083.txt`
- `ziscs0151.txt`
- `ziscs0807.txt`
- `zisdm0020.txt`
- `zisdm0169.txt`
- `zisdm0358.txt`
- `zisfi0036.txt`
- `zisfi0039.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0207.txt`
- `zrcs_remove_cons_af.txt`
- `zsdsoc001.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_