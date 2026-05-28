# ZE31WHERE
**Description:** ACL:Enterprise Agent Selection criteria RFC structure
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `ze31bkgd`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME` | CHAR | 30 |  | Table Name |
| 2 | `TABALIAS` | CHAR | 6 |  | Character field of length 6 |
| 3 | `FIELDNAME` | CHAR | 30 |  | Name of the DB field |
| 4 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 5 | `OPTION` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 6 | `LOW` | CHAR | 100 |  | LOW field of select options table |
| 7 | `HIGH` | CHAR | 100 |  | HIGH field of select options table |
| 8 | `OPERATOR` | CHAR | 3 |  | 3-Byte field |
| 9 | `FIELDTEXT` | CHAR | 80 |  | SAP Query (S): Text of length 80 |
