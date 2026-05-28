# ZISCSEEC_EMLTMPL
**Description:** Email Templates
**Total Fields:** 11
**Key Fields:** MANDT, OBJ_NAME, EML_TEMPL_NAME, LANGU, EMAIL_ELEMENT, SEQ

## Programs Using This Table
- `ziscrm0316`
- `ziscs0532`
- `ziscs0807`
- `ziscs_sms02`
- `ziscseec_eml_postman_bcs`
- `ziscseec_eml_postman_radica`
- `zisfi0310b`
- `zisfi0313`
- `zisfi0320`
- `zisfi0335`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `EML_TEMPL_NAME` | CHAR | 20 | 🔑 | Function of the email |
| 4 | `LANGU` | LANG | 1 | 🔑 | Language Key |
| 5 | `EMAIL_ELEMENT` | CHAR | 10 | 🔑 | Email Element (from, subject, content) |
| 6 | `SEQ` | INT4 | 10 | 🔑 | Natural number |
| 7 | `CONTENT` | CHAR | 1200 |  | Email Content text |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 11 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
