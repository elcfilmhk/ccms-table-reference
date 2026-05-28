# ZISDMPROFPARM
**Description:** Load Profile Import parameter
**Total Fields:** 4
**Key Fields:** MANDT, PARM_NAME

## Programs Using This Table
- `zised0013`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PARM_NAME` | CHAR | 15 | 🔑 | The parameter name |
| 3 | `VALUE` | DEC | 10 |  | The value parameter |
| 4 | `TEXT` | CHAR | 50 |  | The text parameter |
