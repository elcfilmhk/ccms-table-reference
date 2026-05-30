# `DD01L`

**Description:** Data Type — ABAP data type definitions
**Category:** Standard SAP Table
**References:** 6 SELECT statements across 4 programs
**Source:** [leanx.eu](https://leanx.eu/sap/table/dd01l/) — validated 2026-05-30, schema v1.0
**Schema fields:** 26 fields | **Data types:** CHAR(17), DATS(1), LANG(1), NUMC(6), TIMS(1)

## Key Fields

## Field Definitions (leanx.eu)
| Field | Data Element | Checktable | Type | Length | Decimals | Description |
|-------|-------------|------------|------|--------|----------|-------------|
| `DATATYPE` | DATATYPE_D | — | CHAR | 4 | 0 | Data Type in ABAP Dictionary |
| `LENG` | DDLENG | — | NUMC | 6 | 0 | Length (No. of Characters) |
| `OUTPUTLEN` | OUTPUTLEN | — | NUMC | 6 | 0 | Output Length |
| `DECIMALS` | DECIMALS | — | NUMC | 6 | 0 | Number of Decimal Places |
| `LOWERCASE` | LOWERCASE | — | CHAR | 1 | 0 | Lowercase letters allowed/not allowed |
| `SIGNFLAG` | SIGNFLAG | — | CHAR | 1 | 0 | Flag for sign in numerical fields |
| `LANGFLAG` | LANGFLAG | — | CHAR | 1 | 0 | Flag for language-dependent values(not used) |
| `VALEXI` | VALEXI | — | CHAR | 1 | 0 | Existence of fixed values |
| `ENTITYTAB` | ENTITYTAB | DD02L | CHAR | 30 | 0 | Value table |
| `CONVEXIT` | CONVEXIT | — | CHAR | 5 | 0 | Conversion Routine |
| `MASK` | AS4MASK | — | CHAR | 20 | 0 | Template (not used) |
| `MASKLEN` | MASKLEN | — | NUMC | 4 | 0 | Template length (not used) |
| `ACTFLAG` | ACTFLAG | — | CHAR | 1 | 0 | Activation flag |
| `APPLCLASS` | APPLCLASS | — | CHAR | 4 | 0 | Application class for DD objects (not used) |
| `AUTHCLASS` | AUTHCLASS_ | — | NUMC | 2 | 0 | Activation type |
| `AS4USER` | AS4USER | — | CHAR | 12 | 0 | Last Changed by |
| `AS4DATE` | AS4DATE | — | DATS | 8 | 0 | Date of Last Change |
| `AS4TIME` | AS4TIME | — | TIMS | 6 | 0 | Last changed at |
| `DOMMASTER` | MASTERLANG | — | LANG | 1 | 0 | Original Language in Repository objects |
| `RESERVEDOM` | RESERVEDOM | — | CHAR | 4 | 0 | Reserve for domains (not used) |
| `DOMGLOBAL` | GLOBALFLAG | — | CHAR | 1 | 0 | Flag for private DD objects (not used) |
| `APPENDNAME` | DOMNAME | — | CHAR | 30 | 0 | Domain name |
| `APPEXIST` | DDAPPEXI | — | CHAR | 1 | 0 | DD: Indicator that at least one domain append exists |
| `PROXYTYPE` | DDPROXYTY | — | CHAR | 1 | 0 | DD: Is a generated proxy object |
| `OUTPUTSTYLE` | OUTPUTSTYLE | — | NUMC | 2 | 0 | DD: Output Style (Output Style) for Decfloat Types |
| `AMPMFORMAT` | DDAMPMFORMAT | — | CHAR | 1 | 0 | DD: Indicator whether AM/PM time format is required |

## Foreign Key Relationships (leanx.eu)
| Field | FK Table | FK Field | Check Table | Check Field | Description |
|-------|----------|----------|-------------|-------------|-------------|
| `ENTITYTAB` | DD01L | ENTITYTAB | DD02L |  | |
| `ENTITYTAB` | * |  | DD02L |  | |
| `ENTITYTAB` | * |  | DD02L |  | |

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
- `zjivs_set_export_selections.txt`

---
_Generated from SELECT statement analysis across 17,169 ABAP source files in CCMS repo_