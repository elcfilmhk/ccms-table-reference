# ZISBIMSGMKTEXLST
**Description:** Bill messages that do not check for marketing consent
**Total Fields:** 6
**Key Fields:** MANDT, SIGN, OPTI, LOW, HIGH

## Programs Using This Table
- `zisbi0174`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SIGN` | CHAR | 1 | 🔑 | ABAP: ID: I/E (include/exclude values) |
| 3 | `OPTI` | CHAR | 2 | 🔑 | ABAP: Selection option (EQ/BT/CP/...) |
| 4 | `LOW` | NUMC | 10 | 🔑 | Message number |
| 5 | `HIGH` | NUMC | 10 | 🔑 | Message number |
| 6 | `REMARK` | CHAR | 100 |  | Remark which allow lower case |
