# ZVEE_TRACK
**Description:** VEE: Profile Status Tracking
**Total Fields:** 14
**Key Fields:** MANDT, PROFILE, VALUEDAY

## Programs Using This Table
- `z_vee_post_import_validation==ft`
- `zcl_im_isu_edm_proflist_t`
- `zisdm0209_ev`
- `zised0062`
- `zredm_profile_stat_rep`
- `zrvee_post_import_validation`
- `zrvee_pre_bill_estimation`
- `zrvee_prof_rebalance`
- `zrvee_pst_imp_vd_chld`
- `zrvee_report`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 3 | `VALUEDAY` | DATS | 8 | 🔑 | Day of profile values |
| 4 | `STATUS` | NUMC | 2 |  | Status |
| 5 | `VAL_DATE` | DATS | 8 |  | Validated date |
| 6 | `VAL_TIME` | TIMS | 6 |  | Validated time |
| 7 | `EST_DATE` | DATS | 8 |  | Estimated date |
| 8 | `EST_TIME` | TIMS | 6 |  | Estimated time |
| 9 | `AENAME` | CHAR | 12 |  | Name of person who changed object |
| 10 | `AEDATE` | DATS | 8 |  | Date of Last Change |
| 11 | `AEZEIT` | TIMS | 6 |  | Time of Change |
| 12 | `ERRORCODE` | CHAR | 3 |  | Error Code for Replacement Value Procedure |
| 13 | `ATTRNAME` | CHAR | 15 |  | Name of error attribute |
| 14 | `ATTRVALUE` | CHAR | 80 |  | Error attribute value |
