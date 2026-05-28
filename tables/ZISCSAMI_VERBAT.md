# ZISCSAMI_VERBAT
**Description:** Table to store Verbatim Messages for Push Notifications
**Total Fields:** 6
**Key Fields:** MANDT, UNIQU_ATTRIB, VKONT

## Programs Using This Table
- `ziscrm0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNIQU_ATTRIB` | CHAR | 32 | 🔑 | Table-Mantainence friendly UUID (Copied from SYSUUID_C) |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `SENT_TIMESTAMP` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `MESSAGE_EN` | CHAR | 500 |  | Notification Message Sent to Customer(English) |
| 6 | `MESSAGE_ZH` | CHAR | 500 |  | Notification Message Sent to Customer(Chinese) |
