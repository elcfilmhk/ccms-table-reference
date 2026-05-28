# ZISDMAGENDA
**Description:** General Custom Table for DM
**Total Fields:** 5
**Key Fields:** MANDT, OBJ_NAME, TYPE, COUNTER

## Programs Using This Table
- `zcl_isdm_evtou_mig_rpt`
- `zisdm0305`
- `zisdm0410`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `TYPE` | CHAR | 30 | 🔑 | ABAP: Name of Variant Variable |
| 4 | `COUNTER` | NUMC | 4 | 🔑 | ABAP: Current selection number |
| 5 | `VALUE` | CHAR | 45 |  | ABAP: Selection Value (LOW or HIGH Value, External Format) |
