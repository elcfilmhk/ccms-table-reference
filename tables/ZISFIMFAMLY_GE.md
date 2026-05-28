# ZISFIMFAMLY_GE
**Description:** Monthly Parameters (Gas and Extraordinary Items)
**Total Fields:** 26
**Key Fields:** MANDT, TARIFF_YEAR, TARIFF_MONTH, VERSION

## Programs Using This Table
- `zisfi0297`
- `zisfi0299`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFF_YEAR` | NUMC | 4 | 🔑 | Tariff Year |
| 3 | `TARIFF_MONTH` | NUMC | 2 | 🔑 | Tariff Month |
| 4 | `VERSION` | NUMC | 2 | 🔑 | Version |
| 5 | `ACTUAL_GAS_CONS` | DEC | 23 |  | Actual Gas Consumption |
| 6 | `GAS_CONS_UNIT` | CHAR | 12 |  | Unit |
| 7 | `EXT_COAL_COST` | DEC | 23 |  | Extraordinary Coal Cost |
| 8 | `EXT_COAL_UNIT` | CHAR | 12 |  | Unit |
| 9 | `EXT_GAS_COST` | DEC | 23 |  | Extraordinary Gas Cost |
| 10 | `EXT_GAS_UNIT` | CHAR | 12 |  | Unit |
| 11 | `EXT_OIL_COST` | DEC | 23 |  | Extraordinary Oil Cost |
| 12 | `EXT_OIL_UNIT` | CHAR | 12 |  | Unit |
| 13 | `LOCK_FLAG` | CHAR | 1 |  | Lock Flag |
| 14 | `CANCELLED_FLAG` | CHAR | 1 |  | Cancelled Flag |
| 15 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 16 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 17 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 18 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 19 | `AEZEIT` | TIMS | 6 |  | Time of Change |
| 20 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 21 | `LOCK_ON` | DATS | 8 |  | Lock On |
| 22 | `LOCK_AT` | TIMS | 6 |  | Lock At |
| 23 | `LOCK_BY` | CHAR | 12 |  | Lock By |
| 24 | `UNLOCK_ON` | DATS | 8 |  | Unlock On |
| 25 | `UNLOCK_AT` | TIMS | 6 |  | Unlock At |
| 26 | `UNLOCK_BY` | CHAR | 12 |  | Unlock By |
