# ZISDM_POD
**Description:** Customized Structure for FM Z_ISDM_METER_REMOVAL
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_meter_removal==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 3 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 4 | `LOGIKZW` | NUMC | 18 |  | Logical register number |
| 5 | `INT_UI` | CHAR | 22 |  | Internal key for point of delivery |
| 6 | `DATETO` | DATS | 8 |  | Valid-To Date |
| 7 | `TIMETO` | TIMS | 6 |  | End time |
| 8 | `EXT_UI` | CHAR | 50 |  | Point of delivery ID |
