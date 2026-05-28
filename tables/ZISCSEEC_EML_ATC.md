# ZISCSEEC_EML_ATC
**Description:** Email Attachments
**Total Fields:** 7
**Key Fields:** MANDT, REQ_DT, REQ_PROG_NAME, GUID, SEQ

## Programs Using This Table
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
| 6 | `FILE_PATH` | CHAR | 1024 |  | Case-Sensitive Length 1024 |
| 7 | `NEW_FILE_NAME` | CHAR | 100 |  | Text (100 characters) |
