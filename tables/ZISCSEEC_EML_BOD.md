# ZISCSEEC_EML_BOD
**Description:** Table to store email body
**Total Fields:** 6
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
| 6 | `EML_CONTENT` | CHAR | 255 |  | Text field length 255: texts |
