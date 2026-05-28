# `DFKKKO`

**Description:** CA Document Header — FI-CA document header
**Category:** Standard SAP Table
**References:** 174 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `OPBEL` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `BLART`, `BUDAT`, `CPUDT`, `ERNAM`, `HERKF`, `OPBEL`, `STBEL`, `STORB`, `XBLNR`, `blart`, `budat`, `cpudt`, `ernam`, `fikey`, `herkf`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `BLART`, `STORB`, `XBLNR`, `blart`, `budat`, `cpudt`, `opbel`, `stbel`, `xblnr`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_isbi_reverseclr_rebill.txt`
- `zisbi0032.txt`
- `zisbi0225f01.txt`
- `ziscs0088.txt`
- `ziscs0517forms.txt`
- `ziscs1118.txt`
- `ziscs_migration_adjustment.txt`
- `ziscs_migration_financial_tran.txt`
- `zisfi0036.txt`
- `zisfi0069.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0131.txt`
- `zisfi0139.txt`
- `zisfi0238_bw.txt`
- `zisfi0300.txt`
- `zisfi0351.txt`
- `zissd00063.txt`
- `zprintdoc.txt`
- `zzrepair.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
