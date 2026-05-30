# `DD03L`

**Description:** Table Field — DDIC field definitions
**Category:** Standard SAP Table
**References:** 95 SELECT statements across 20 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dd03l/) — validated 2026-05-30, schema v1.0
**Schema fields:** 25 fields | **Data types:** CHAR(19), NUMC(6)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `KEYFLAG` | KEYFLAG | — | CHAR | 1 | 0 | Identifies a key field of a table |
| `MANDATORY` | MANDATORY | — | CHAR | 1 | 0 | Flag: Field is required (not blank) |
| `ROLLNAME` | ROLLNAME | DD04L | CHAR | 30 | 0 | Data element (semantic domain) |
| `CHECKTABLE` | CHECKTABLE | — | CHAR | 30 | 0 | Check table name of the foreign key |
| `ADMINFIELD` | ADMINFIELD | — | CHAR | 1 | 0 | Nesting depth for includes |
| `INTTYPE` | INTTYPE | — | CHAR | 1 | 0 | ABAP data type (C,D,N,...) |
| `INTLEN` | INTLEN | — | NUMC | 6 | 0 | Internal Length in Bytes |
| `REFTABLE` | REFTABLE | — | CHAR | 30 | 0 | Table for reference field |
| `PRECFIELD` | PRECFIELD | — | CHAR | 30 | 0 | Name of included table |
| `REFFIELD` | REFFIELD | — | CHAR | 30 | 0 | Reference field for currency and qty fields |
| `CONROUT` | CONROUT | — | CHAR | 10 | 0 | Check or generating module for fields |
| `NOTNULL` | NOTNULL | — | CHAR | 1 | 0 | Indicator that NOT NULL is forced for this field |
| `DATATYPE` | DATATYPE_D | — | CHAR | 4 | 0 | Data Type in ABAP Dictionary |
| `LENG` | DDLENG | — | NUMC | 6 | 0 | Length (No. of Characters) |
| `DECIMALS` | DECIMALS | — | NUMC | 6 | 0 | Number of Decimal Places |
| `DOMNAME` | DOMNAME | DD01L | CHAR | 30 | 0 | Domain name |
| `SHLPORIGIN` | SHLPORIGIN | — | CHAR | 1 | 0 | Origin of an Input Help |
| `TABLETYPE` | DDTABTYPE | — | CHAR | 1 | 0 | DD: Flag if it is a table |
| `DEPTH` | TYPEDEPTH | — | NUMC | 2 | 0 | DD: Depth for structured types |
| `COMPTYPE` | COMPTYPE | — | CHAR | 1 | 0 | DD: Component Type |
| `REFTYPE` | DDREFTYPE | — | CHAR | 1 | 0 | Type of Object Referenced |
| `LANGUFLAG` | DDLANGUFLG | — | CHAR | 1 | 0 | DD: Indicator for a Language Field |
| `DBPOSITION` | TABFDPOS | — | NUMC | 4 | 0 | Position of the field in the table |
| `ANONYMOUS` | DDANONYM | — | CHAR | 1 | 0 | Anonymization Indicator (for User Fields) |
| `OUTPUTSTYLE` | OUTPUTSTYLE | — | NUMC | 2 | 0 | DD: Output Style (Output Style) for Decfloat Types |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `DOMNAME` | DD03L | DOMNAME | DD01L |  | |
| `DOMNAME` | * |  | DD01L |  | |
| `DOMNAME` | * |  | DD01L |  | |
| `ROLLNAME` | DD03L | ROLLNAME | DD04L |  | |
| `ROLLNAME` | * |  | DD04L |  | |
| `ROLLNAME` | * |  | DD04L |  | |
| `TABNAME` | DD03L | TABNAME | DD02L |  | |
| `TABNAME` | * |  | DD02L |  | |
| `TABNAME` | * |  | DD02L |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `z_fi_fill_fkkvkp_s_di.txt`
- `zbacbe034.txt`
- `zbacbe106_ssa_cat.txt`
- `zcazzi000.txt`
- `ziscrmact_queue.txt`
- `ziscs0601i02.txt`
- `ziscs_pon_export_ca.txt`
- `ziscs_pon_import_sent_hist.txt`
- `ziscv_datamask_thread.txt`
- `zisdm0098.txt`
- `zisdm0430_alv.txt`
- `zjivs_create_table_count.txt`
- `zjivs_export_info.txt`
- `zjivs_export_pclx.txt`
- `zjivs_hana.txt`
- `zjivs_rollname.txt`
- `zjivs_set_export_selections.txt`
- `zmmpri000.txt`
- `znewhdb_size.txt`
- `zziscv_datamask_thread.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_