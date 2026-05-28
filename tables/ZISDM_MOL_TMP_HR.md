# ZISDM_MOL_TMP_HR
**Description:** Hourly Actual Table
**Total Fields:** 8
**Key Fields:** MANDT, WEA_FC_LOCATION, WEA_DATE, WEA_TIME

## Programs Using This Table
- `zisdm_mol_key_change_migration`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `WEA_FC_LOCATION` | CHAR | 8 | 🔑 | Location of Forecast |
| 3 | `WEA_DATE` | DATS | 8 | 🔑 | Date |
| 4 | `WEA_TIME` | CHAR | 2 | 🔑 | MOL Hourly Timeslot |
| 5 | `TEM` | DEC | 31 |  | MOL equation parameters |
| 6 | `HUM` | DEC | 31 |  | MOL equation parameters |
| 7 | `ENTHALPY` | DEC | 31 |  | MOL equation parameters |
| 8 | `STATUS` | CHAR | 1 |  | MOL Status |
