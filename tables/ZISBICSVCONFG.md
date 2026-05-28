# ZISBICSVCONFG
**Description:** Report CSV Configuration
**Total Fields:** 5
**Key Fields:** MANDT, RPTTYPE, OBJ_NAME, COUNTER

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`
- `zopenpdf`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPTTYPE` | CHAR | 8 | 🔑 | Report Type |
| 3 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 4 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `VALUE` | CHAR | 45 |  | ABAP: Selection Value (LOW or HIGH Value, External Format) |
