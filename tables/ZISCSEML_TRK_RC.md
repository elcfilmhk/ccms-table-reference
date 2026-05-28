# ZISCSEML_TRK_RC
**Description:** Email Tracking Platform - Email Recipients
**Total Fields:** 5
**Key Fields:** MANDT, REQ_DT, EML_GUID, RCPT_EML_TOKEN

## Programs Using This Table
- `ziscs0478_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REQ_DT` | CHAR | 14 | 🔑 | Request Email Datetime |
| 3 | `EML_GUID` | CHAR | 32 | 🔑 | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 4 | `RCPT_EML_TOKEN` | CHAR | 32 | 🔑 | Recipient Email Address Token |
| 5 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
