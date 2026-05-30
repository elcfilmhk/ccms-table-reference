# `VBEP`

**Description:** Sales Document Schedule Line — delivery schedule
**Category:** Standard SAP Table
**References:** 10 SELECT statements across 7 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbep/) — validated 2026-05-30, schema v1.0
**Schema fields:** 57 fields | **Data types:** CHAR(22), DATS(10), DEC(2), FLTP(1), NUMC(6), QUAN(7), TIMS(6), UNIT(3)

## Key Fields
`AUFNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ETTYP` | ETTYP | TVEP | CHAR | 2 | 0 | Schedule line category |
| `LFREL` | LFREL | — | CHAR | 1 | 0 | Item is relevant for delivery |
| `EDATU` | EDATU | — | DATS | 8 | 0 | Schedule line date |
| `EZEIT` | EZEIT_VBEP | — | TIMS | 6 | 0 | Arrival time |
| `WMENG` | WMENG | — | QUAN | 13 | 3 | Order quantity in sales units |
| `BMENG` | BMENG | — | QUAN | 13 | 3 | Confirmed Quantity |
| `VRKME` | VRKME | T006 | UNIT | 3 | 0 | Sales unit |
| `LMENG` | LMENG | — | QUAN | 13 | 3 | Required quantity for mat.management in stockkeeping units |
| `MEINS` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `BDDAT` | BDDAT | — | DATS | 8 | 0 | Requirement date (deadline for procurement) |
| `BDART` | BDART | — | CHAR | 2 | 0 | Requirement type |
| `PLART` | PLART | — | CHAR | 1 | 0 | Planning type |
| `VBELE` | VBELE | VBUK | CHAR | 10 | 0 | Business document number |
| `POSNE` | POSNE | VBUP | NUMC | 6 | 0 | Business item number |
| `ETENE` | ETENE | VBEP | NUMC | 4 | 0 | Schedule line |
| `RSDAT` | RSDAT | — | DATS | 8 | 0 | Earliest possible reservation date |
| `IDNNR` | IDNNR | — | NUMC | 10 | 0 | Maintenance request |
| `BANFN` | BANFN | — | CHAR | 10 | 0 | Purchase Requisition Number |
| `BSART` | BSART | T161 | CHAR | 4 | 0 | Order Type (Purchasing) |
| `BSTYP` | BSTYP | — | CHAR | 1 | 0 | Purchasing Document Category |
| `WEPOS` | WEPOS_A | — | CHAR | 1 | 0 | Confirmation status of schedule line (incl.ALE) |
| `REPOS` | REPOS | — | CHAR | 1 | 0 | Invoice Receipt Indicator |
| `LRGDT` | LRGDT | — | DATS | 8 | 0 | Return date for returnable packaging |
| `PRGRS` | PRGRS | — | CHAR | 1 | 0 | Date type (day, week, month, interval) |
| `TDDAT` | TDDAT_D | — | DATS | 8 | 0 | Transportation Planning Date |
| `MBDAT` | MBDAT | — | DATS | 8 | 0 | Material Staging/Availability Date |
| `LDDAT` | LDDAT | — | DATS | 8 | 0 | Loading Date |
| `WADAT` | WADAT | — | DATS | 8 | 0 | Goods Issue Date |
| `CMENG` | CMENG | — | QUAN | 13 | 3 | Corrected quantity in sales unit |
| `LIFSP` | LIFSP_EP | TVLS | CHAR | 2 | 0 | Schedule line blocked for delivery |
| `GRSTR` | GRSTR | — | NUMC | 3 | 0 | Group definition of structure data |
| `ABART` | ABART | — | CHAR | 1 | 0 | Release type |
| `ABRUF` | ABRUF | — | NUMC | 10 | 0 | Forecast Delivery schedule number |
| `ROMS1` | DCQNT | — | QUAN | 13 | 3 | Committed quantity |
| `ROMS2` | ROMS2 | — | QUAN | 13 | 3 | Size 2 |
| `ROMS3` | ROMS3 | — | QUAN | 13 | 3 | Size 3 |
| `ROMEI` | ROMEI | T006 | UNIT | 3 | 0 | Unit of measure for sizes 1 to 3 |
| `RFORM` | RFORM | — | CHAR | 2 | 0 | Formula key |
| `UMVKZ` | UMVKZ | — | DEC | 5 | 0 | Numerator (factor) for conversion of sales quantity into SKU |
| `UMVKN` | UMVKN | — | DEC | 5 | 0 | Denominator (Divisor) for Conversion of Sales Qty into SKU |
| `VERFP` | VERFP_MAS | — | CHAR | 1 | 0 | Availability confirmed automatically |
| `BWART` | BWART | T156 | CHAR | 3 | 0 | Movement Type (Inventory Management) |
| `BNFPO` | BNFPO | EBAN | NUMC | 5 | 0 | Item Number of Purchase Requisition |
| `ETART` | EDI_ETTYP | TVET | CHAR | 1 | 0 | Schedule line type EDI |
| `AUFNR` | AUFNR | AUFK | CHAR | 12 | 0 | Order Number |
| `PLNUM` | PLNUM | PLAF | CHAR | 10 | 0 | Planned order number |
| `SERNR` | SERNR | SNUM | CHAR | 8 | 0 | BOM explosion number |
| `AESKD` | AESKD | — | CHAR | 17 | 0 | Customer Engineering Change Status |
| `ABGES` | ABGES_CM | — | FLTP | 16 | 16 | Guaranteed (factor between 0 and 1) |
| `MBUHR` | MBUHR | — | TIMS | 6 | 0 | Material Staging Time (Local, Relating to a Plant) |
| `TDUHR` | TDUHR | — | TIMS | 6 | 0 | Transp. Planning Time (Local, Relating to a Shipping Point) |
| `LDUHR` | LDUHR | — | TIMS | 6 | 0 | Loading Time (Local Time Relating to a Shipping Point) |
| `WAUHR` | WAUHR | — | TIMS | 6 | 0 | Time of Goods Issue (Local, Relating to a Plant) |
| `AULWE` | AULWE | VALW | CHAR | 10 | 0 | Route Schedule |
| `HANDOVERDATE` | HANDOVER_DATE | — | DATS | 8 | 0 | Handover Date at the Handover Location |
| `HANDOVERTIME` | HANDOVER_TIME | — | TIMS | 6 | 0 | Handover time at the handover location |
| `MBDAT_DRS` | MBDAT_DRS | — | DATS | 8 | 0 | Material Availability Date Third-Party Order Planning |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `AUFNR` | VBEP | MANDT | AUFK |  | |
| `AUFNR` | VBEP | AUFNR | AUFK |  | |
| `AULWE` | VBEP | MANDT | VALW |  | |
| `AULWE` | VBEP | AULWE | VALW |  | |
| `BNFPO` | VBEP | MANDT | EBAN |  | |
| `BNFPO` | VBEP | BANFN | EBAN |  | |
| `BNFPO` | VBEP | BNFPO | EBAN |  | |
| `BSART` | VBEP | MANDT | T161 |  | |
| `BSART` | VBEP | BSTYP | T161 |  | |
| `BSART` | VBEP | BSART | T161 |  | |
| `BWART` | VBEP | MANDT | T156 |  | |
| `BWART` | VBEP | BWART | T156 |  | |
| `ETART` | VBEP | MANDT | TVET |  | |
| `ETART` | VBEP | ETART | TVET |  | |
| `ETENE` | VBEP | ETENE | VBEP |  | |
| `ETENE` | VBEP | MANDT | VBEP |  | |
| `ETENE` | VBEP | VBELE | VBEP |  | |
| `ETENE` | VBEP | POSNE | VBEP |  | |
| `ETTYP` | VBEP | ETTYP | TVEP |  | |
| `ETTYP` | VBEP | MANDT | TVEP |  | |
| `LIFSP` | VBEP | MANDT | TVLS |  | |
| `LIFSP` | VBEP | LIFSP | TVLS |  | |
| `MANDT` | VBEP | MANDT | T000 |  | |
| `MEINS` | VBEP | MEINS | T006 |  | |
| `MEINS` | VBEP | MANDT | T006 |  | |
| `PLNUM` | VBEP | PLNUM | PLAF |  | |
| `PLNUM` | VBEP | MANDT | PLAF |  | |
| `POSNE` | VBEP | VBELE | VBUP |  | |
| `POSNE` | VBEP | POSNE | VBUP |  | |
| `POSNE` | VBEP | MANDT | VBUP |  | |
| `POSNR` | VBEP | MANDT | VBUP |  | |
| `POSNR` | VBEP | VBELN | VBUP |  | |
| `POSNR` | VBEP | POSNR | VBUP |  | |
| `ROMEI` | VBEP | MANDT | T006 |  | |
| `ROMEI` | VBEP | ROMEI | T006 |  | |
| `SERNR` | VBEP | MANDT | SNUM |  | |
| `SERNR` | VBEP | SERNR | SNUM |  | |
| `VBELE` | VBEP | MANDT | VBUK |  | |
| `VBELE` | VBEP | VBELE | VBUK |  | |
| `VBELN` | VBEP | MANDT | VBUK |  | |
| `VBELN` | VBEP | VBELN | VBUK |  | |
| `VRKME` | VBEP | MANDT | T006 |  | |
| `VRKME` | VBEP | VRKME | T006 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zissd00072.txt`
- `zissd00086.txt`
- `zissd00097.txt`
- `zissd00098.txt`
- `zsdsoblk1.txt`
- `zsdsoc001.txt`
- `zsdsocbo1.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_