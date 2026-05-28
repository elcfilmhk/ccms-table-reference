# ZISDM_MOL_ALT_TP
**Description:** Email Template for MOL Proactive Alert
**Total Fields:** 6
**Key Fields:** MANDT, EMAILID, SECTIONID, SEQ, LANGU

## Programs Using This Table
- `zisdm0293`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EMAILID` | CHAR | 1 | 🔑 | Single-Character Flag |
| 3 | `SECTIONID` | CHAR | 1 | 🔑 | Single-Character Flag |
| 4 | `SEQ` | INT1 | 3 | 🔑 | Sequence |
| 5 | `LANGU` | LANG | 1 | 🔑 | Language Key |
| 6 | `CONTENT` | CHAR | 255 |  | Email Content |
