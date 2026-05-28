# `EABL`

**Description:** Installation Register — meter register at a device location
**Category:** Standard SAP Table
**References:** 540 SELECT statements across 20 programs

## Key Fields
| Field | Type | Key | Description |
|-------|------|-----|-------------|
| `MANDT` | | 🔑 | Primary key |
| `ANLAGE` | | 🔑 | Primary key |
| `ABLBELNR` | | 🔑 | Primary key |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ABLBELNR`, `ABLSTAT`, `ADAT`, `ATIM`, `EQUNR`, `GERNR`, `N_ZWSTAND`, `V_ZWSTAND`, `ZWNUMMER`, `ablbelnr`, `ablesart`, `ableser`, `ablestyp`, `ablhinw`, `ablstat`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `EQUNR`, `ablbelnr`, `ablstat`, `adat`, `adatsoll`, `aedat`, `equnr`, `gernr`, `zwnummer`

## Join Paths
- `EABL.ANLAGE` → `EANL.ANLAGE` — Register → Installation
- `EABL.EQUNR` → `EQUI.EQUNR` — Register → Equipment
- `EABL.ABLBELNR` → `EABLG.ABLBELNR` — Register → Register History

## Programs Using This Table
- `z_isdm_create_grpbill_chkread.txt`
- `ziscs0184.txt`
- `ziscs0273.txt`
- `ziscs0525_f01.txt`
- `ziscs_migration_estimate_read.txt`
- `zisdatveri.txt`
- `zisdm0116.txt`
- `zisdm0152.txt`
- `zisdm0159.txt`
- `zisdm0169.txt`
- `zisdm0170.txt`
- `zisdm0172.txt`
- `zisdm0201.txt`
- `zisdm0201_sub_lp.txt`
- `zisdm0204f01.txt`
- `zisdm0215.txt`
- `zisdm0246.txt`
- `zisdm0272.txt`
- `zismd0038_recon.txt`
- `zwfm_get_mr_order_details.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_
