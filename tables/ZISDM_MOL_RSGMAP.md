# ZISDM_MOL_RSGMAP
**Description:** Region Structure Group to Forecast Location Mapping
**Total Fields:** 4
**Key Fields:** MANDT, REGIOGROUP, EFFECT_FROM

## Programs Using This Table
- `zisdm0286`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGIOGROUP` | CHAR | 8 | 🔑 | Regional structure grouping |
| 3 | `EFFECT_FROM` | DATS | 8 | 🔑 | Effect From |
| 4 | `FC_LOC_CODE` | CHAR | 8 |  | Location of Forecast |
