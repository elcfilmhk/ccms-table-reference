# ZISCSCOMM_TMPL
**Description:** Determine Communication Template Table
**Total Fields:** 6
**Key Fields:** MANDT, MESSAGETYPE, SUB_MESSAGE_TYPE, COMM_CHANNEL

## Programs Using This Table
- `ziscs_sms02`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MESSAGETYPE` | CHAR | 2 | 🔑 | Message Type |
| 3 | `SUB_MESSAGE_TYPE` | CHAR | 3 | 🔑 | Sub Message Type |
| 4 | `COMM_CHANNEL` | CHAR | 1 | 🔑 | Communication Channel |
| 5 | `MESSAGETEMPLATE` | CHAR | 20 |  | Template Name for Email, SMS or MPush message |
| 6 | `DESCRIPTION` | CHAR | 50 |  | Sub Message Description |
