# ZJIVS_COLUMN
**Description:** Description of one table column
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_initial_setup`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `COLUMNNAME` | CHAR | 30 |  | Field name (for set) |
| 2 | `TYPENAME` | CHAR | 4 |  | Data Type in ABAP Dictionary |
| 3 | `KEYFLAG` | CHAR | 1 |  | Identifies a key field of a table |
| 4 | `COLUMNSIZE` | NUMC | 6 |  | Length (No. of Characters) |
| 5 | `DECIMALDIGITS` | NUMC | 6 |  | Number of Decimal Places |
| 6 | `INTTYPE` | CHAR | 1 |  | ABAP data type (C,D,N,...) |
| 7 | `INTLEN` | NUMC | 6 |  | Internal Length in Bytes |
| 8 | `DESCRIPTION` | CHAR | 60 |  | Short Description of Repository Objects |
| 9 | `NULLABLE` | CHAR | 1 |  | Single-Character Flag |
| 10 | `SPRAS` | CHAR | 1 |  | Single-Character Flag |
