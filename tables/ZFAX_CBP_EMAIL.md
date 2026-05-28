# ZFAX_CBP_EMAIL
**Description:** Automated Change BP/Acct Email
**Total Fields:** 6
**Key Fields:** MANDT, OBJ_NAME, EMAIL_ELEMENT, FUNCTION, SEQ

## Programs Using This Table
- `ziscs0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `EMAIL_ELEMENT` | CHAR | 10 | 🔑 | Email Element (from, subject, content) |
| 4 | `FUNCTION` | CHAR | 20 | 🔑 | Function of the email |
| 5 | `SEQ` | CHAR | 2 | 🔑 | Sequence number |
| 6 | `CONTENT` | CHAR | 255 |  | Content |
