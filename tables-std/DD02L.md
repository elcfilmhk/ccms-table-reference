# `DD02L`

**Description:** Table — DDIC table definitions
**Category:** Standard SAP Table
**References:** 43 SELECT statements across 18 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dd02l/) — validated 2026-05-30, schema v1.0
**Schema fields:** 29 fields | **Data types:** CHAR(20), DATS(1), LANG(1), NUMC(6), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `TABCLASS` | TABCLASS | — | CHAR | 8 | 0 | Table category |
| `SQLTAB` | SQLAPPDTAB | — | CHAR | 30 | 0 | Name of an SQL table or an appended table |
| `DATMIN` | DATMIN | — | NUMC | 10 | 0 | Minimum no. of entries |
| `DATMAX` | DATMAX | — | NUMC | 10 | 0 | Maximum no. of entries |
| `DATAVG` | DATAVG | — | NUMC | 10 | 0 | Average number of entries |
| `CLIDEP` | CLIDEP | — | CHAR | 1 | 0 | Flag indicating client-specific entries |
| `BUFFERED` | BUFFERED | — | CHAR | 1 | 0 | Buffering flag |
| `COMPRFLAG` | COMPREX | — | CHAR | 1 | 0 | Field compression indicator |
| `LANGDEP` | LANGDEP | — | CHAR | 1 | 0 | Language dependency |
| `ACTFLAG` | ACTFLAG | — | CHAR | 1 | 0 | Activation flag |
| `APPLCLASS` | APPLCLASS | — | CHAR | 4 | 0 | Application class for DD objects (not used) |
| `AUTHCLASS` | AUTHCLASS_ | — | NUMC | 2 | 0 | Activation type |
| `AS4USER` | AS4USER | — | CHAR | 12 | 0 | Last Changed by |
| `AS4DATE` | AS4DATE | — | DATS | 8 | 0 | Date of Last Change |
| `AS4TIME` | AS4TIME | — | TIMS | 6 | 0 | Last changed at |
| `MASTERLANG` | MASTERLANG | — | LANG | 1 | 0 | Original Language in Repository objects |
| `MAINFLAG` | MAINTFLAG | — | CHAR | 1 | 0 | Flag if Maintenance with Standard Tools is allowed |
| `CONTFLAG` | CONTFLAG | — | CHAR | 1 | 0 | Delivery class |
| `RESERVETAB` | RESERVETAB | — | CHAR | 4 | 0 | SDIC: Reserve for tables |
| `GLOBALFLAG` | GLOBALFLAG | — | CHAR | 1 | 0 | Flag for private DD objects (not used) |
| `PROZPUFF` | PROZPUFF | — | NUMC | 3 | 0 | Percentage for buffers |
| `VIEWCLASS` | VIEWCLASS | — | CHAR | 1 | 0 | View Type |
| `VIEWGRANT` | VIEWGRANT | — | CHAR | 1 | 0 | Maintenance status (modif. authorization) for view data |
| `MULTIPLEX` | MULTIPLEX | — | CHAR | 1 | 0 | Indicator whether multiplexing is possible for a table |
| `SHLPEXI` | SHLPEXI | — | CHAR | 1 | 0 | Search help attachment to table exists |
| `PROXYTYPE` | DDPROXYTY | — | CHAR | 1 | 0 | DD: Is a generated proxy object |
| `EXCLASS` | DDRANKING | — | NUMC | 1 | 0 | DD:  Ranking for include and subtype extension |
| `WRONGCL` | DDWRONGCL | — | CHAR | 1 | 0 | Enhancement category is incorrect |
| `ALWAYSTRP` | DDALWAYSTRP | — | CHAR | 1 | 0 | Table is always transparent on selective database |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe023.txt`
- `zbacbe024.txt`
- `zbacbe034.txt`
- `zbacbe100.txt`
- `zbacbe101.txt`
- `zbacbe106_get_rows_count.txt`
- `zbacbe106_ssa_cat.txt`
- `zbacbe201_f01.txt`
- `zjivs_delim_check.txt`
- `zjivs_dyn_adk.txt`
- `zjivs_export_info.txt`
- `zjivs_export_job.txt`
- `zjivs_export_pai.txt`
- `zjivs_hana.txt`
- `zjivs_rollname.txt`
- `zjivs_set_export_selections.txt`
- `zjivs_system_info_check.txt`
- `znewhdb_size.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_