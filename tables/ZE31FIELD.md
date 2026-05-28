# ZE31FIELD
**Description:** ACL:Enterprise Agent Table field info RFC structure
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `ze31bkgd`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME` | CHAR | 30 |  | Table Name |
| 2 | `TABALIAS` | CHAR | 6 |  | Character field of length 6 |
| 3 | `FIELDNAME` | CHAR | 30 |  | Name of the DB field |
| 4 | `OFFSET` | NUMC | 6 |  | Offset of a field |
| 5 | `LENGTH` | NUMC | 6 |  | Length (No. of Characters) |
| 6 | `TYPE` | CHAR | 4 |  | Data type of screen field |
| 7 | `DECIMALS` | NUMC | 6 |  | Number of Decimal Places |
| 8 | `KEY_FLAG` | CHAR | 1 |  | Identifies a key field of a table |
| 9 | `FIELDTEXT` | CHAR | 60 |  | Short Description of Repository Objects |
| 10 | `INTLEN` | NUMC | 6 |  | Internal Length in Bytes |
