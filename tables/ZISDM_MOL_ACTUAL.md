# ZISDM_MOL_ACTUAL
**Description:** MOL Actual Table
**Total Fields:** 8
**Key Fields:** MANDT, WEA_FC_LOCATION, WEA_DATE

## Programs Using This Table
- `zisdm0286`
- `zisdm0288`
- `zisdm0290`
- `zisdm0291`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `WEA_FC_LOCATION` | CHAR | 8 | 🔑 | Location of Forecast |
| 3 | `WEA_DATE` | DATS | 8 | 🔑 | Date |
| 4 | `OPGROUP` | CHAR | 10 |  | Operating time groups |
| 5 | `TEM_AVG` | DEC | 31 |  | MOL equation parameters |
| 6 | `HUM_AVG` | DEC | 31 |  | MOL equation parameters |
| 7 | `ENTHALPY` | DEC | 31 |  | MOL equation parameters |
| 8 | `STATUS` | CHAR | 1 |  | MOL Status |
