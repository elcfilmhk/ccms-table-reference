# `EANLH`

**Description:** Installation History — installation validity periods
**Category:** Standard SAP Table
**References:** 560 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |

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
