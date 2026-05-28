# ZISGENERALDATA
**Description:** General Custom Table to populate data
**Total Fields:** 8
**Key Fields:** MANDT, OBJ_NAME, TYPE, COUNTER

## Programs Using This Table
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `TYPE` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 4 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `SIGN` | CHAR | 1 |  | ABAP: ID: I/E (include/exclude values) |
| 6 | `OPTI` | CHAR | 2 |  | ABAP: Selection option (EQ/BT/CP/...) |
| 7 | `LOW` | CHAR | 255 |  | ABAP: Selection Value (LOW or HIGH Value, External Format) |
| 8 | `HIGH` | CHAR | 255 |  | ABAP: Selection Value (LOW or HIGH Value, External Format) |
