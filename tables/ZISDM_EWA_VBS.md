# ZISDM_EWA_VBS
**Description:** Maintain Premise saleable floor area log
**Total Fields:** 10
**Key Fields:** MANDT, VSTELLE, AEDAT, AETIM, AB

## Programs Using This Table
- `zisdm0302`
- `zisdm0306`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `AEDAT` | DATS | 8 | 🔑 | Date of Last Change |
| 4 | `AETIM` | TIMS | 6 | 🔑 | Time |
| 5 | `AB` | DATS | 8 | 🔑 | Date from which time slice is valid |
| 6 | `FT2` | DEC | 9 |  | Floor Area in Square Feet |
| 7 | `FAREA` | DEC | 9 |  | Input floor area |
| 8 | `UOM` | CHAR | 3 |  | Input Floor area UOM |
| 9 | `AREA_NATURE` | CHAR | 1 |  | Input area nature |
| 10 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
