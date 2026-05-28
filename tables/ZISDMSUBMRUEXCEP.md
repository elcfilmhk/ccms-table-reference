# ZISDMSUBMRUEXCEP
**Description:** Table of variables in selection criteria
**Total Fields:** 8
**Key Fields:** MANDT, NAME, TYPE, NUMB

## Programs Using This Table
- `zisdh0005`
- `zisdm0344`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NAME` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 3 | `TYPE` | CHAR | 1 | 🔑 | ABAP: Type of selection |
| 4 | `NUMB` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 6 | `OPTI` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 7 | `LOW` | CHAR | 255 |  | Selection Variants: Field Content (LOW/HIGH) |
| 8 | `HIGH` | CHAR | 255 |  | Selection Variants: Field Content (LOW/HIGH) |
