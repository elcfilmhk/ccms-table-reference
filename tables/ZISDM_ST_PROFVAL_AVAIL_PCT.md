# ZISDM_ST_PROFVAL_AVAIL_PCT
**Description:** Percentage of available load profile
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0429`
- `zisdm_bapi_profval_avail_pct==ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ANLAGE` | CHAR | 10 |  | Installation |
| 2 | `NO_OF_DAYS` | NUMC | 4 |  | Count parameters |
| 3 | `TOTAL_INTERVAL` | NUMC | 10 |  | Numeric Character Field, Length 10 |
| 4 | `PROF_VAL_FOUND` | NUMC | 10 |  | Numeric Character Field, Length 10 |
| 5 | `AVAIL_PCT` | NUMC | 3 |  | Numc3, internal use |
