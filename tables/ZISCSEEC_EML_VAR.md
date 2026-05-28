# ZISCSEEC_EML_VAR
**Description:** Email template tag value pairs
**Total Fields:** 7
**Key Fields:** MANDT, REQ_DT, REQ_PROG_NAME, GUID, SEQ, VAR_NAME

## Programs Using This Table
- `ziscs0841`
- `ziscseec_eml_postman_bcs`
- `ziscseec_eml_postman_radica`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `REQ_PROG_NAME` | CHAR | 40 | 🔑 | ABAP Program Name |
| 4 | `GUID` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 5 | `SEQ` | INT4 | 10 | 🔑 | Natural number |
| 6 | `VAR_NAME` | CHAR | 100 | 🔑 | Name of variables in EE&C email template |
| 7 | `VAR_VALUE` | STRG | 0 |  | Value to VAR_NAME |
