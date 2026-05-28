# ZCDAGENDA
**Description:** Change doc. items for custom configs like ZISDMAGENDA
**Total Fields:** 13
**Key Fields:** MANDT, TABNAME, OBJ_NAME, TYPE, COUNTER, FNAME, UDATE, UTIME

## Programs Using This Table
- `zisdm0410`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 3 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 4 | `TYPE` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 5 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 6 | `FNAME` | CHAR | 30 | 🔑 | Field Name |
| 7 | `UDATE` | DATS | 8 | 🔑 | Creation date of the change document |
| 8 | `UTIME` | TIMS | 6 | 🔑 | Time changed |
| 9 | `TCODE` | CHAR | 20 |  | Transaction in which a change was made |
| 10 | `VALUE_NEW` | CHAR | 254 |  | New contents of changed field |
| 11 | `VALUE_OLD` | CHAR | 254 |  | Old contents of changed field |
| 12 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 13 | `PROGRAMM` | CHAR | 40 |  | ABAP Program Name |
