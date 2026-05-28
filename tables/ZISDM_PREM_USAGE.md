# ZISDM_PREM_USAGE
**Description:** Premise Usage Data
**Total Fields:** 16
**Key Fields:** MANDT, VSTELLE, VKONTO, AEDAT, AETIM

## Programs Using This Table
- `zisdm0324`
- `zisdm0325`
- `zisdm0326`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `AEDAT` | DATS | 8 | 🔑 | Date of Last Change |
| 5 | `AETIM` | TIMS | 6 | 🔑 | Time |
| 6 | `BUILDING_TYPE` | CHAR | 3 |  | Premise Building Type |
| 7 | `FUNCTION` | CHAR | 3 |  | Premise Function |
| 8 | `OCCUPANCY` | CHAR | 3 |  | Premise Occupancy |
| 9 | `PREM_CHANGE_DATE` | DATS | 8 |  | Date from which time slice is valid |
| 10 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 11 | `CHANGE` | CHAR | 3 |  | Premise Usage Data Change Indicator |
| 12 | `CREATED_ON` | DATS | 8 |  | Date of Last Change |
| 13 | `CREATED_ON_TIME` | TIMS | 6 |  | Time |
| 14 | `CREATED_BY` | CHAR | 12 |  | Name of person who changed object |
| 15 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 16 | `LATEST` | CHAR | 1 |  | Latest Premise Usage Data Indicator |
