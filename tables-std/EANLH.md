# `EANLH`

**Description:** Installation History — installation validity periods
**Category:** Standard SAP Table
**References:** 560 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/eanlh/) — validated 2026-05-30, schema v1.0
**Schema fields:** 23 fields | **Data types:** CHAR(22), DATS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `AB` | ABZEITSCH | — | DATS | 8 | 0 | Date from which time slice is valid |
| `TARIFTYP` | TARIFTYP_ANL | ETTA | CHAR | 10 | 0 | Rate category |
| `ANLSTAT` | ANLSTAT | — | CHAR | 2 | 0 | Installation Status |
| `KONZBEFR` | KONZBEFR | — | CHAR | 1 | 0 | Exempt from franchise fee |
| `PAUSCHAL` | E_PAUSCHAL | — | CHAR | 1 | 0 | Device allocation is not possible |
| `BRANCHE` | BU_IND_SECTOR | TB038A | CHAR | 10 | 0 | Industry |
| `AKLASSE` | AKLASSE | EAKLASSE | CHAR | 4 | 0 | Billing class |
| `ABLEINH` | ABLEINHEIT | TE422 | CHAR | 8 | 0 | Meter Reading Unit |
| `TEMP_AREA` | TEMP_AREA | TE307 | CHAR | 8 | 0 | Temperature area |
| `KONZVER` | KONZVER | — | CHAR | 10 | 0 | Franchise contract |
| `BILLING_PARTY` | BILLING_PARTY | — | CHAR | 10 | 0 | Service Provider that Bills the Installation |
| `INVOICING_PARTY` | INVOICING_PARTY | — | CHAR | 10 | 0 | Service Provider That Invoices the Contract |
| `PROV_LAST_RES` | PROV_LAST_RESSORT | — | CHAR | 10 | 0 | Obligation to Supply |
| `MAININST` | MAININST | EANL | CHAR | 10 | 0 | Key of Primary Installation |
| `INSTROLE` | INSTROLE | TE673 | CHAR | 4 | 0 | Role of an Installation Within the Installation Group |
| `INSTGRTYPE` | INSTGRTYPE | TE672 | CHAR | 4 | 0 | Grouping Type for Installation Group |
| `ISTYPE` | BU_ISTYPE | TB038 | CHAR | 4 | 0 | Industry System |
| `HIGHLEVINST` | HIGHLEVINST | EANL | CHAR | 10 | 0 | Higher-Level Installation |
| `SCHEMANR` | SCHEMANR | ESCH | CHAR | 10 | 0 | Number of the billing schema |
| `HOCHART` | HOCHART | — | CHAR | 1 | 0 | Type of extrapolation in unbilled revenue reporting |
| `VPERGRUP` | VPERGRUP | — | CHAR | 4 | 0 | Previous period control group |
| `PRUEFGR` | PRUEFGR | TE413 | CHAR | 4 | 0 | Validation group for dependent validations |
| `ABSSTEU` | ABSSTEU | — | CHAR | 1 | 0 | Budget billing control |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ABLEINH` | EANLH | MANDT | TE422 |  | |
| `ABLEINH` | EANLH | ABLEINH | TE422 |  | |
| `AKLASSE` | EANLH | MANDT | EAKLASSE |  | |
| `AKLASSE` | EANLH | AKLASSE | EAKLASSE |  | |
| `ANLAGE` | EANLH | MANDT | EANL |  | |
| `ANLAGE` | EANLH | ANLAGE | EANL |  | |
| `BRANCHE` | EANLH | ISTYPE | TB038A |  | |
| `BRANCHE` | EANLH | BRANCHE | TB038A |  | |
| `BRANCHE` | SYST | MANDT | TB038A |  | |
| `HIGHLEVINST` | SYST | MANDT | EANL |  | |
| `HIGHLEVINST` | EANLH | HIGHLEVINST | EANL |  | |
| `INSTGRTYPE` | SYST | MANDT | TE672 |  | |
| `INSTGRTYPE` | EANLH | INSTGRTYPE | TE672 |  | |
| `INSTROLE` | EANLH | INSTROLE | TE673 |  | |
| `INSTROLE` | SYST | MANDT | TE673 |  | |
| `ISTYPE` | SYST | MANDT | TB038 |  | |
| `ISTYPE` | EANLH | ISTYPE | TB038 |  | |
| `MAININST` | SYST | MANDT | EANL |  | |
| `MAININST` | EANLH | MAININST | EANL |  | |
| `MANDT` | EANLH | MANDT | T000 |  | |
| `PRUEFGR` | * |  | TE413 |  | |
| `PRUEFGR` | EANLH | PRUEFGR | TE413 |  | |
| `SCHEMANR` | * |  | ESCH |  | |
| `SCHEMANR` | EANLH | SCHEMANR | ESCH |  | |
| `TARIFTYP` | EANLH | TARIFTYP | ETTA |  | |
| `TARIFTYP` | EANLH | MANDT | ETTA |  | |
| `TEMP_AREA` | EANLH | MANDT | TE307 |  | |
| `TEMP_AREA` | EANLH | TEMP_AREA | TE307 |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `AB`, `AEI`, `AKLASSE`, `ANLAGE`, `BIS`, `TARIFTYP`, `ab`, `ableinh`, `aklasse`, `anlage`, `bis`, `instgrtype`, `instrole`, `maininst`, `tariftyp`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `ANLAGE`, `ableinh`, `anlage`, `bis`, `tariftyp`

## Join Paths
- `EANLH.EQUNR` → `EQUI.EQUNR` — Installation History → Equipment

## Programs Using This Table
- `zis_write_bwami_extractor.txt`
- `zisbi0055.txt`
- `zisbi0106.txt`
- `ziscs0031.txt`
- `ziscs0086b.txt`
- `ziscs0151.txt`
- `ziscs0169_old.txt`
- `ziscs0170.txt`
- `ziscs0226f_f01.txt`
- `ziscs0243.txt`
- `ziscs0526_f01.txt`
- `zisdm0067.txt`
- `zisdm0086.txt`
- `zisdm0203_rbtolp.txt`
- `zisdm0261.txt`
- `zisdm0322.txt`
- `zisfi0036.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisu_edm_formula_0010.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_