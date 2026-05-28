# ZISDMMRGENWKORD
**Description:** Work orders generated during MR upload
**Total Fields:** 5
**Key Fields:** MANDT, RUNDATE, ABLBELNR, AUFNR

## Programs Using This Table
- `zisdm0050`
- `zisdm0142`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Date of Program Run |
| 3 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 4 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 5 | `ILART` | CHAR | 3 |  | Maintenance activity type |
