# ZISCSEML_TRK_FIL
**Description:** Email Tracking Platform - CSV Field mapping config
**Total Fields:** 11
**Key Fields:** MANDT, EMP_PROVIDER, FILE_TYPE, SEQ

## Programs Using This Table
- `ziscs0478_eec`
- `ziscs_eml_trk_csv_map_vals====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMP_PROVIDER` | CHAR | 50 | 🔑 | Provider/Vendor of email event tracking |
| 3 | `FILE_TYPE` | CHAR | 20 | 🔑 | CSV File Type Code |
| 4 | `SEQ` | INT4 | 10 | 🔑 | Natural number |
| 5 | `COL_LABEL` | CHAR | 100 |  | CSV Column Label |
| 6 | `FIELD_FORMAT_FM` | CHAR | 30 |  | CSV Field Formatting Function Module |
| 7 | `DB_FIELDNAME` | CHAR | 50 |  | DB Field Name |
| 8 | `SAVE_HD_VAR` | CHAR | 1 |  | Single-Character Flag |
| 9 | `SAVE_EVNT_VAR` | CHAR | 1 |  | Single-Character Flag |
| 10 | `FURTHER_SPLIT_FM` | CHAR | 30 |  | CSV Field further splitting Function Module |
| 11 | `CASE_SENSITIVE` | CHAR | 1 |  | Single-Character Flag |
