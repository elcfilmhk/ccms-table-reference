# `VBFA`

**Description:** Sales Document Flow — document flow/log
**Category:** Standard SAP Table
**References:** 24 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/vbfa/) — validated 2026-05-30, schema v1.0
**Schema fields:** 37 fields | **Data types:** CHAR(18), CUKY(1), CURR(1), DATS(2), FLTP(3), NUMC(3), QUAN(4), TIMS(1), UNIT(4)

## Key Fields
`MATNR`

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `RFMNG` | RFMNG | — | QUAN | 15 | 3 | Referenced quantity in base unit of measure |
| `MEINS` | MEINS | T006 | UNIT | 3 | 0 | Base Unit of Measure |
| `RFWRT` | RFWRT | — | CURR | 15 | 2 | Reference value |
| `WAERS` | WAERS_V | TCURC | CUKY | 5 | 0 | Statistics currency |
| `VBTYP_V` | VBTYP_V | — | CHAR | 1 | 0 | Document category of preceding SD document |
| `PLMIN` | PLMIN | — | CHAR | 1 | 0 | Quantity is calculated positively, negatively or not at all |
| `TAQUI` | TAQUI | — | CHAR | 1 | 0 | ID: MM-WM transfer order confirmed |
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERZET` | ERZET | — | TIMS | 6 | 0 | Entry time |
| `MATNR` | MATNR | MARA | CHAR | 18 | 0 | Material Number |
| `BWART` | BWART | T156 | CHAR | 3 | 0 | Movement Type (Inventory Management) |
| `BDART` | BDART | — | CHAR | 2 | 0 | Requirement type |
| `PLART` | PLART | — | CHAR | 1 | 0 | Planning type |
| `STUFE` | STUFE_VBFA | — | NUMC | 2 | 0 | Level of the document flow record |
| `LGNUM` | LGNUM | T300 | CHAR | 3 | 0 | Warehouse Number / Warehouse Complex |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `FKTYP` | FKTYP | — | CHAR | 1 | 0 | Billing category |
| `BRGEW` | BRGEW_15 | — | QUAN | 15 | 3 | Gross weight |
| `GEWEI` | GEWEI | — | UNIT | 3 | 0 | Weight Unit |
| `VOLUM` | VOLUM_15 | — | QUAN | 15 | 3 | Volume |
| `VOLEH` | VOLEH | — | UNIT | 3 | 0 | Volume unit |
| `FPLNR` | FPLNR | FPLA | CHAR | 10 | 0 | Billing plan number / invoicing plan number |
| `FPLTR` | FPLTR | — | NUMC | 6 | 0 | Item for billing plan/invoice plan/payment cards |
| `RFMNG_FLO` | RFMNG_FLTV | — | FLTP | 16 | 16 | Referenced quantity in sales unit (float) |
| `RFMNG_FLT` | RFMNG_FLT | — | FLTP | 16 | 16 | Referenced quantity in base unit of measure (float) |
| `VRKME` | VRKME | T006 | UNIT | 3 | 0 | Sales unit |
| `ABGES` | ABGES_CM | — | FLTP | 16 | 16 | Guaranteed (factor between 0 and 1) |
| `SOBKZ` | SOBKZ | — | CHAR | 1 | 0 | Special Stock Indicator |
| `SONUM` | LVS_SONUM | — | CHAR | 16 | 0 | Special Stock Number |
| `KZBEF` | LVS_KZBEF | — | CHAR | 1 | 0 | Indicator Inventory Management active |
| `NTGEW` | NTGEW | — | QUAN | 13 | 3 | Net Weight |
| `LOGSYS` | LOGSYS | TBDLS | CHAR | 10 | 0 | Logical system |
| `WBSTA` | WBSTA | — | CHAR | 1 | 0 | Goods movement status |
| `CMETH` | OIB_CMETH | — | CHAR | 1 | 0 | Quantity Conversion Method |
| `MJAHR` | MJAHR | — | NUMC | 4 | 0 | Material Document Year |
| `VBTYPEXT_V` | TDD_VBTYP_EXT_V | — | CHAR | 4 | 0 | Extension of SD document category of preceding document |
| `VBTYPEXT_N` | TDD_VBTYP_EXT_N | — | CHAR | 4 | 0 | Extension of Subsequent SD Document Category |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `BWART` | VBFA | MANDT | T156 |  | |
| `BWART` | VBFA | BWART | T156 |  | |
| `FPLNR` | VBFA | MANDT | FPLA |  | |
| `FPLNR` | VBFA | FPLNR | FPLA |  | |
| `LGNUM` | VBFA | MANDT | T300 |  | |
| `LGNUM` | VBFA | LGNUM | T300 |  | |
| `LOGSYS` | VBFA | LOGSYS | TBDLS |  | |
| `MANDT` | VBFA | MANDT | T000 |  | |
| `MATNR` | VBFA | MANDT | MARA |  | |
| `MATNR` | VBFA | MATNR | MARA |  | |
| `MEINS` | VBFA | MEINS | T006 |  | |
| `MEINS` | VBFA | MANDT | T006 |  | |
| `POSNN` | VBFA | POSNN | VBUP |  | |
| `POSNN` | VBFA | MANDT | VBUP |  | |
| `POSNN` | VBFA | VBELN | VBUP |  | |
| `POSNV` | VBFA | MANDT | VBUP |  | |
| `POSNV` | VBFA | VBELV | VBUP |  | |
| `POSNV` | VBFA | POSNV | VBUP |  | |
| `VBELN` | VBFA | MANDT | VBUK |  | |
| `VBELN` | VBFA | VBELN | VBUK |  | |
| `VBELV` | VBFA | MANDT | VBUK |  | |
| `VBELV` | VBFA | VBELV | VBUK |  | |
| `VRKME` | VBFA | MANDT | T006 |  | |
| `VRKME` | VBFA | VRKME | T006 |  | |
| `WAERS` | VBFA | MANDT | TCURC |  | |
| `WAERS` | VBFA | WAERS | TCURC |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ZO1`

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zisfi0121.txt`
- `zisfi0238.txt`
- `zisfi0238_bw.txt`
- `zissd00017.txt`
- `zissd00018.txt`
- `zissd00019.txt`
- `zissd00020.txt`
- `zissd00058.txt`
- `zissd00059.txt`
- `zissd00060.txt`
- `zissd00061.txt`
- `zissd00062.txt`
- `zissd00086.txt`
- `zissd00088.txt`
- `zissd00097.txt`
- `zissd00100.txt`
- `zsdisqry05.txt`
- `zsdsoblk1.txt`
- `zsdsodl01.txt`
- `zsdsodl05.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_