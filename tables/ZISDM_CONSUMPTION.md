# ZISDM_CONSUMPTION
**Description:** Consumption and Incentive Table for MOL For DT
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0221`
- `zisdm0222`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `START_DATE` | DATS | 8 |  | Start Date of the incentive record |
| 2 | `END_DATE` | DATS | 8 |  | End Date of the incentive record |
| 3 | `PEAK_PERCENT` | DEC | 5 |  | Peak hour consumption ratio |
| 4 | `INCENTIVE` | DEC | 5 |  | Incentive amount |
| 5 | `INCOMPLETE` | CHAR | 1 |  | Incomplete month indicator |
