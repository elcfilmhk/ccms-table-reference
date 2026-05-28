# ZISCSEML_TRK_EV
**Description:** Email Tracking Platform - Email Events Header
**Total Fields:** 7
**Key Fields:** MANDT, REQ_DT, EML_GUID, RCPT_EML_TOKEN, EVNT_DT, EVNT_TYPE

## Programs Using This Table
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`
- `ziscs0478_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | Request Email Datetime |
| 3 | `EML_GUID` | CHAR | 32 | 🔑 | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 4 | `RCPT_EML_TOKEN` | CHAR | 32 | 🔑 | Recipient Email Address Token |
| 5 | `EVNT_DT` | CHAR | 14 | 🔑 | Email Event Datetime |
| 6 | `EVNT_TYPE` | CHAR | 30 | 🔑 | Email Event Type |
| 7 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
