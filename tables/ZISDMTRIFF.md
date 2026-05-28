# ZISDMTRIFF
**Description:** Tariff Table
**Total Fields:** 7
**Key Fields:** MANDT, TARIFTYP

## Programs Using This Table
- `zisdh0002`
- `zisdh0026`
- `zisdm0021`
- `zisdm0027`
- `zisdm0029`
- `zisdm0050`
- `zisdm0058`
- `zisdm0059`
- `zisdm0060`
- `zisdm0082`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `ZZTARIFTYP` | CHAR | 1 |  | Tariff Type (CISS) |
| 4 | `ZZSUBTRFTY` | CHAR | 1 |  | Sub Tariff Type (CISS) |
| 5 | `ZZTARIFABR` | CHAR | 12 |  | Tariff abbreviation |
| 6 | `ZZTARIFDSC` | CHAR | 40 |  | CISS Tariff Description |
| 7 | `ZZTARIFFBASIC` | CHAR | 3 |  | Indicate whether we have a DT, GST, LPT,BT, or OTH customer |
