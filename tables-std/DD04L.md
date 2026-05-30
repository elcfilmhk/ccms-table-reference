# `DD04L`

**Description:** Data Element — DDIC data element definitions
**Category:** Standard SAP Table
**References:** 16 SELECT statements across 3 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dd04l/) — validated 2026-05-30, schema v1.0
**Schema fields:** 35 fields | **Data types:** CHAR(23), DATS(1), LANG(1), NUMC(9), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DOMNAME` | DOMNAME | DD01L | CHAR | 30 | 0 | Domain name |
| `ROUTPUTLEN` | DDLENG | — | NUMC | 6 | 0 | Length (No. of Characters) |
| `MEMORYID` | MEMORYID | TPARA | CHAR | 20 | 0 | Set/Get parameter ID |
| `LOGFLAG` | LOGFLAG | — | CHAR | 1 | 0 | Indicator for writing change documents |
| `HEADLEN` | HEADLEN | — | NUMC | 2 | 0 | Maximum length of heading |
| `SCRLEN1` | SCRLEN_S | — | NUMC | 2 | 0 | Max. length for short field label |
| `SCRLEN2` | SCRLEN_M | — | NUMC | 2 | 0 | Max. length for medium field label |
| `SCRLEN3` | SCRLEN_L | — | NUMC | 2 | 0 | Max. length for long field label |
| `ACTFLAG` | DTACTFLAG | — | CHAR | 1 | 0 | Activation flag |
| `APPLCLASS` | APPLCLASS | — | CHAR | 4 | 0 | Application class for DD objects (not used) |
| `AUTHCLASS` | AUTHCLASS_ | — | NUMC | 2 | 0 | Activation type |
| `AS4USER` | AS4USER | — | CHAR | 12 | 0 | Last Changed by |
| `AS4DATE` | AS4DATE | — | DATS | 8 | 0 | Date of Last Change |
| `AS4TIME` | AS4TIME | — | TIMS | 6 | 0 | Last changed at |
| `DTELMASTER` | MASTERLANG | — | LANG | 1 | 0 | Original Language in Repository objects |
| `RESERVEDTE` | RESERVEDTE | — | CHAR | 4 | 0 | SDIC: Reserve for data elements (not used) |
| `DTELGLOBAL` | GLOBALFLAG | — | CHAR | 1 | 0 | Flag for private DD objects (not used) |
| `SHLPNAME` | SHLPNAME | — | CHAR | 30 | 0 | Name of a Search Help |
| `SHLPFIELD` | SHLPFIELD | — | CHAR | 30 | 0 | Name of a search help parameter |
| `DEFFDNAME` | DEFFDNAME | — | CHAR | 30 | 0 | Default name for components using the data element |
| `DATATYPE` | DATATYPE_D | — | CHAR | 4 | 0 | Data Type in ABAP Dictionary |
| `LENG` | DDLENG | — | NUMC | 6 | 0 | Length (No. of Characters) |
| `DECIMALS` | DECIMALS | — | NUMC | 6 | 0 | Number of Decimal Places |
| `OUTPUTLEN` | OUTPUTLEN | — | NUMC | 6 | 0 | Output Length |
| `LOWERCASE` | LOWERCASE | — | CHAR | 1 | 0 | Lowercase letters allowed/not allowed |
| `SIGNFLAG` | SIGNFLAG | — | CHAR | 1 | 0 | Flag for sign in numerical fields |
| `CONVEXIT` | CONVEXIT | — | CHAR | 5 | 0 | Conversion Routine |
| `VALEXI` | VALEXI | — | CHAR | 1 | 0 | Existence of fixed values |
| `ENTITYTAB` | ENTITYTAB | DD02L | CHAR | 30 | 0 | Value table |
| `REFKIND` | TYPEKIND | — | CHAR | 1 | 0 | Category of Dictionary Type |
| `REFTYPE` | DDREFTYPE | — | CHAR | 1 | 0 | Type of Object Referenced |
| `PROXYTYPE` | DDPROXYTY | — | CHAR | 1 | 0 | DD: Is a generated proxy object |
| `LTRFLDDIS` | DDLTRFLDDI | — | CHAR | 1 | 0 | Basic write direction has been defined LTR (left-to-right) |
| `BIDICTRLC` | DDBIDICTRL | — | CHAR | 1 | 0 | DD: No Filtering of BIDI Formatting Characters |
| `NOHISTORY` | DDNOHISTORY | — | CHAR | 1 | 0 | DD: Flag for Deactivating Input History in Screen Field |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `DOMNAME` | DD04L | DOMNAME | DD01L |  | |
| `DOMNAME` | * |  | DD01L |  | |
| `DOMNAME` | * |  | DD01L |  | |
| `ENTITYTAB` | DD04L | ENTITYTAB | DD02L |  | |
| `ENTITYTAB` | * |  | DD02L |  | |
| `ENTITYTAB` | * |  | DD02L |  | |
| `MEMORYID` | DD04L | MEMORYID | TPARA |  | |

## Detected Join Fields
_No join fields detected in CCMS code_

## Detected WHERE Fields
_No WHERE fields detected in CCMS code_

## Join Paths
_No confirmed join paths — derive from detected fields above_

## Programs Using This Table
- `zbacbe034.txt`
- `zbacbe106_ssa_cat.txt`
- `zjivs_rollname.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_