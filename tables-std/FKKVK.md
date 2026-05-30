# `FKKVK`

**Description:** Contract Account — CA master record
**Category:** Standard SAP Table
**References:** 214 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/fkkvk/) — validated 2026-05-30, schema v1.0
**Schema fields:** 9 fields | **Data types:** CHAR(7), DATS(2)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `ERDAT` | ERDAT | — | DATS | 8 | 0 | Date on Which Record Was Created |
| `ERNAM` | ERNAM | — | CHAR | 12 | 0 | Name of Person who Created the Object |
| `LOEVM` | LOEVM_KK | — | CHAR | 1 | 0 | Mark Contract Account for Deletion |
| `AEDAT` | AEDAT | — | DATS | 8 | 0 | Changed On |
| `AENAM` | AENAM | — | CHAR | 12 | 0 | Name of Person Who Changed Object |
| `APPLK` | APPLK_KK | — | CHAR | 1 | 0 | Application area |
| `VKTYP` | VKTYP_KK | TFK002A | CHAR | 2 | 0 | Contract Account Category |
| `VKONA` | VKONA_KK | — | CHAR | 20 | 0 | Contract account number in legacy system |
| `VKBEZ` | VKBEZ_KK | — | CHAR | 35 | 0 | Contract account name |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `MANDT` | FKKVK | MANDT | T000 |  | |
| `VKTYP` | FKKVK | MANDT | TFK002A |  | |
| `VKTYP` | FKKVK | APPLK | TFK002A |  | |
| `VKTYP` | FKKVK | VKTYP | TFK002A |  | |

## Detected Join Fields
_Fields found in JOIN/ON patterns in CCMS code:_
- `ERDAT`, `VKONT`, `VKTYP`, `loevm`, `vkont`, `vktyp`

## Detected WHERE Fields
_Fields found in WHERE conditions:_
- `VKTYP`, `vkont`, `vktyp`

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_bapi_get_bp_id.txt`
- `z_bapi_get_gs_info.txt`
- `z_bapi_simple_accinfo.txt`
- `z_bapi_webid_forget.txt`
- `z_paymedium_hsbccos_refund.txt`
- `zisbi0006.txt`
- `zisbi0142.txt`
- `ziscrm0006f01.txt`
- `ziscs0151.txt`
- `ziscs0169.txt`
- `ziscs0173.txt`
- `ziscs0195.txt`
- `zisdm0255f01.txt`
- `zisdm0382.txt`
- `zisfi0005_dun.txt`
- `zisfi0039.txt`
- `zisfi0108.txt`
- `zisfi0116_1.txt`
- `zisfi0116_test3.txt`
- `zisfi0149.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_