# ZJIVS_TAB_COLUMN
**Description:** Description of the table fields
**Total Fields:** 11
**Key Fields:** TABCLASS, TABLENAME, COLUMNNAME

## Programs Using This Table
- `zjivs_initial_setup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABCLASS` | CHAR | 8 | 🔑 | Table Category |
| 2 | `TABLENAME` | CHAR | 49 | 🔑 | JiVS Dataelement for tablename |
| 3 | `COLUMNNAME` | CHAR | 30 | 🔑 | Field name (for set) |
| 4 | `POSNR` | INT4 | 10 |  | Natural number |
| 5 | `TYPENAME` | CHAR | 4 |  | Data Type in ABAP Dictionary |
| 6 | `KEYFLAG` | CHAR | 1 |  | Identifies a key field of a table |
| 7 | `COLUMNSIZE` | INT4 | 10 |  | Natural number |
| 8 | `DECIMALDIGITS` | INT4 | 10 |  | Natural number |
| 9 | `NULLABLE` | CHAR | 1 |  | Single-Character Flag |
| 10 | `BINARY_TABLE` | CHAR | 1 |  | Single-Character Flag |
| 11 | `SPRAS` | CHAR | 1 |  | Single-Character Flag |
