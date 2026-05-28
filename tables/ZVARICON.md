# ZVARICON
**Description:** Custom Variant Content
**Total Fields:** 10
**Key Fields:** MANDT, REPORT, VARIANT, FIELDNAME, INDX

## Programs Using This Table
- `zisdm0406`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORT` | CHAR | 40 | 🔑 | ABAP: Program Name in Variant Key |
| 3 | `VARIANT` | CHAR | 14 | 🔑 | ABAP: Name of variant (without program name) |
| 4 | `FIELDNAME` | CHAR | 8 | 🔑 | ABAP: Name of SELECT-OPTION/PARAMETER |
| 5 | `INDX` | INT4 | 10 | 🔑 | Row Index of Internal Tables |
| 6 | `TYPE` | CHAR | 1 |  | ABAP: Type of selection |
| 7 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 8 | `OPTI` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 9 | `LOW` | CHAR | 132 |  | Selection variants: Field content (LOW/HIGH) |
| 10 | `HIGH` | CHAR | 132 |  | Selection variants: Field content (LOW/HIGH) |
