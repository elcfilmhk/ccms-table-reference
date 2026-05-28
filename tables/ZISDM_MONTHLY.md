# ZISDM_MONTHLY
**Description:** Monthly Table for MOL For DT
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0221`
- `zisdm0222`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RECORD_DATE` | DATS | 8 |  | Date of consumption record |
| 2 | `NO_PROFILE` | CHAR | 1 |  | No profile found ('X' - No profile) |
| 3 | `CONSUMPTION` | CHAR | 35 |  | Consumption of the period |
| 4 | `PEAK_PERCENT` | DEC | 5 |  | Peak hour consumption ratio |
