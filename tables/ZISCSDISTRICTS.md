# ZISCSDISTRICTS
**Description:** Districts
**Total Fields:** 4
**Key Fields:** MANDT, REGION, DISTRICT, DISTRICT_C

## Programs Using This Table
- `zcl_z_clp_online_mpc`
- `zcl_z_clp_online_zzz_mpc`
- `ziscs0201`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGION` | CHAR | 3 | 🔑 | Region (State, Province, County) |
| 3 | `DISTRICT` | CHAR | 40 | 🔑 | District, the address line with ADRC-nation = space |
| 4 | `DISTRICT_C` | CHAR | 40 | 🔑 | District in Chinese, the address line with ADRC-nation = 'M' |
