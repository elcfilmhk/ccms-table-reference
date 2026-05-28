# ZISCRMMYWSCONF
**Description:** My Work Space Configuration Table
**Total Fields:** 9
**Key Fields:** MANDT, OBJ_NAME, FUNCTION

## Programs Using This Table
- `ziscrm0009`
- `ziscrm0011`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `FUNCTION` | CHAR | 4 | 🔑 | Interface control - function name |
| 4 | `CURR_NUM` | NUMC | 8 |  | MyWorkSpace - Current number |
| 5 | `NEXT_NUM` | NUMC | 8 |  | MyWorkSpace - Next number |
| 6 | `DESCRIPTION` | CHAR | 30 |  | Description |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 8 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 9 | `AEZEIT` | TIMS | 6 |  | Time of Change |
