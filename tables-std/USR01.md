# `USR01`

**Description:** User Address — user master address
**Category:** Standard SAP Table
**References:** 23 SELECT statements across 16 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/usr01/) — validated 2026-05-30, schema v1.0
**Schema fields:** 16 fields | **Data types:** CHAR(14), CLNT(1), LANG(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `STCOD` | XUSTCOD | — | CHAR | 20 | 0 | Start menu (old, replaced by XUSTART) |
| `SPLD` | RSPOPNAME | TSP03 | CHAR | 4 | 0 | Spool: Output device |
| `SPLG` | XUSPLG | — | CHAR | 1 | 0 | Print parameter 1 |
| `SPDB` | XUSPDB | — | CHAR | 1 | 0 | Print parameter 2 |
| `SPDA` | XUSPDA | — | CHAR | 1 | 0 | Print parameter 3 |
| `DATFM` | XUDATFM | — | CHAR | 1 | 0 | Date format |
| `DCPFM` | XUDCPFM | — | CHAR | 1 | 0 | Decimal Format |
| `HDEST` | XUHDEST | — | CHAR | 8 | 0 | Host destination |
| `HMAND` | XUHMAND | — | CLNT | 3 | 0 | Default host client |
| `HNAME` | XUHNAME | — | CHAR | 12 | 0 | Default host user name |
| `MENON` | XUMENON | — | CHAR | 1 | 0 | Automatic Start |
| `MENUE` | XUMENUE | — | CHAR | 20 | 0 | Menu name |
| `STRTT` | XUSTCOD | — | CHAR | 20 | 0 | Start menu (old, replaced by XUSTART) |
| `LANGU` | XULANGU | — | LANG | 1 | 0 | Logon Language |
| `CATTKENNZ` | XUCATT | — | CHAR | 1 | 0 | CATT: Test Status |
| `TIMEFM` | XUTIMEFM | — | CHAR | 1 | 0 | Time Format (12-/24-Hour Specification) |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `SPLD` | USR01 | SPLD | TSP03 |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_isdm_check_upper_limit.txt`
- `z_isdm_truncate_dec.txt`
- `z_isdm_truncate_dec_etdz.txt`
- `zbaicri02.txt`
- `zbaicri07.txt`
- `zca_doc.txt`
- `zficfdl02.txt`
- `zficfdl05.txt`
- `ziscs0261f01.txt`
- `zisdm0050.txt`
- `zisdm0051.txt`
- `zisfi0250.txt`
- `zisfi0250_backup.txt`
- `zisfi0250_backup_1.txt`
- `zjivs_set_export_selections.txt`
- `zrfkkze01.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_