# ZISCSEML_TRK_EV1
**Description:** Email Tracking Platform - Email Events Misc Fields
**Total Fields:** 10
**Key Fields:** MANDT, REQ_DT, EML_GUID, RCPT_EML_TOKEN, EVNT_DT, EVNT_TYPE, VAR_NAME

## Programs Using This Table
- `zisbi0232`
- `zisbi0233`
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
| 7 | `VAR_NAME` | CHAR | 100 | 🔑 | Name of variables in EE&C email template |
| 8 | `VAR_VALUE` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 9 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 10 | `DELETE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
