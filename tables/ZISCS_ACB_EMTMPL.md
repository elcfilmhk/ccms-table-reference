# ZISCS_ACB_EMTMPL
**Description:** ACB Tripping Notification Email/SMS Templates
**Total Fields:** 7
**Key Fields:** MANDT, OBJ_NAME, EML_TEMPL_NAME, LANGU, EMAIL_ELEMENT, SEQ

## Programs Using This Table
- `ziscs0408`

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
