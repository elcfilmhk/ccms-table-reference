# ZISCSEML_ADDR_TK
**Description:** Email Tracking Platform - Email Recipients
**Total Fields:** 4
**Key Fields:** MANDT, RCPT_EML_TOKEN

## Programs Using This Table
- `zisbi0232`
- `zisbi0233`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RCPT_EML_TOKEN` | CHAR | 32 | 🔑 | Recipient Email Address Token |
| 3 | `RCPT_EML_ADDR` | CHAR | 80 |  | Single Email Recipient Email Address |
| 4 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
