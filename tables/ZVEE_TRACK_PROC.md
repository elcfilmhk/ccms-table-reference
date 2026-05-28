# ZVEE_TRACK_PROC
**Description:** VEE: Profile Status Updated Tracking Temp Table
**Total Fields:** 4
**Key Fields:** MANDT, RUNID, PROFILE, VALUEDAY

## Programs Using This Table
- `zrvee_post_import_validation`
- `zrvee_pst_imp_vd_chld`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNID` | NUMC | 10 | 🔑 | Numeric Character Field, Length 10 |
| 3 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 4 | `VALUEDAY` | DATS | 8 | 🔑 | Day of profile values |
