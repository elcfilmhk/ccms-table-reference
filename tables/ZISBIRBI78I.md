# ZISBIRBI78I
**Description:** Data from RBI78I
**Total Fields:** 7
**Key Fields:** MANDT, RPT_TYP, OBJ_KEY, ABRDATS

## Programs Using This Table
- `zisbi0042`
- `zisbi0042_ami`
- `zisbi0104`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPT_TYP` | CHAR | 4 | 🔑 | Report type |
| 3 | `OBJ_KEY` | CHAR | 12 | 🔑 | Billing doc / Print doc / Installation |
| 4 | `ABRDATS` | DATS | 8 | 🔑 | Scheduled Billing Date |
| 5 | `VALIDATION` | CHAR | 10 |  | Name of billing validation |
| 6 | `UNBL_REASON` | CHAR | 255 |  | Text of a Line of a Message |
| 7 | `AENAM` | CHAR | 12 |  | User name of the person responsible in change document |
