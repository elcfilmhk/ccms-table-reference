# ZISDMLPBCVCONFIG
**Description:** Conversion configuration for LP installation
**Total Fields:** 4
**Key Fields:** MANDT, METER_CONFIG, METER_ROLE, IDENT_RATE_TYPE

## Programs Using This Table
- `zisdm0203`
- `zisdm0203_cbtolp`
- `zisdm0203_rbtolp`
- `zisdm0294`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METER_CONFIG` | CHAR | 10 | 🔑 | Meter Configuration |
| 3 | `METER_ROLE` | CHAR | 10 | 🔑 | The Meter Role to be converted to LP Biling |
| 4 | `IDENT_RATE_TYPE` | CHAR | 8 | 🔑 | Rate Type |
