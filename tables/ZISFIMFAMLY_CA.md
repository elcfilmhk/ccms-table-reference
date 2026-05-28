# ZISFIMFAMLY_CA
**Description:** Monthly Parameters (China Sales-GPG and Adjustment Items)
**Total Fields:** 36
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
| 5 | `CHINA_COAL_COST` | DEC | 23 |  | China Sales Coal Cost |
| 6 | `CHINA_COAL_COST_UNIT` | CHAR | 12 |  | Unit |
| 7 | `CHINA_GAS_COST` | DEC | 23 |  | China Sales Gas Cost |
| 8 | `CHINA_GAS_COST_UNIT` | CHAR | 12 |  | Unit |
| 9 | `CHINA_OIL_COST` | DEC | 23 |  | China Sales Oil Cost |
| 10 | `CHINA_OIL_COST_UNIT` | CHAR | 12 |  | Unit |
| 11 | `CHINA_COAL_CONS` | DEC | 23 |  | China Sales Coal Consumption |
| 12 | `CHINA_COAL_CONS_UNIT` | CHAR | 12 |  | Unit |
| 13 | `CHINA_GAS_CONS` | DEC | 23 |  | China Sales Gas Consumption |
| 14 | `CHINA_GAS_CONS_UNIT` | CHAR | 12 |  | Unit |
| 15 | `CHINA_OIL_CONS` | DEC | 23 |  | China Sales Oil Consumption |
| 16 | `CHINA_OIL_CONS_UNIT` | CHAR | 12 |  | Unit |
| 17 | `ADJUSTMENT_COAL_CONS` | DEC | 23 |  | Adjustment Coal Consumption |
| 18 | `ADJ_COAL_CONS_UNIT` | CHAR | 12 |  | Unit |
| 19 | `ADJUSTMENT_GAS_CONS` | DEC | 23 |  | Adjustment Gas Consumption |
| 20 | `ADJ_GAS_CONS_UNIT` | CHAR | 12 |  | Unit |
| 21 | `ADJUSTMENT_OIL_CONS` | DEC | 23 |  | Adjustment Oil Consumption |
| 22 | `ADJ_OIL_CONS_UNIT` | CHAR | 12 |  | Unit |
| 23 | `LOCK_FLAG` | CHAR | 1 |  | Lock Flag |
| 24 | `CANCELLED_FLAG` | CHAR | 1 |  | Cancelled Flag |
| 25 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 26 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 27 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 28 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 29 | `AEZEIT` | TIMS | 6 |  | Time of Change |
| 30 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 31 | `LOCK_ON` | DATS | 8 |  | Lock On |
| 32 | `LOCK_AT` | TIMS | 6 |  | Lock At |
| 33 | `LOCK_BY` | CHAR | 12 |  | Lock By |
| 34 | `UNLOCK_ON` | DATS | 8 |  | Unlock On |
| 35 | `UNLOCK_AT` | TIMS | 6 |  | Unlock At |
| 36 | `UNLOCK_BY` | CHAR | 12 |  | Unlock By |
