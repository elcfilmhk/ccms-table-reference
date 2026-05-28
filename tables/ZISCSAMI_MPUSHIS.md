# ZISCSAMI_MPUSHIS
**Description:** History Table for Mobile Push Notifications
**Total Fields:** 11
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
| 5 | `DEV_TOKEN` | CHAR | 256 |  | Device Token |
| 6 | `APPLICATION` | CHAR | 20 |  | Application |
| 7 | `MESSAGE_TYPE` | CHAR | 2 |  | Message Type |
| 8 | `ORIG_MES_LANG` | LANG | 1 |  | Notification Language |
| 9 | `DEV_TYPE` | CHAR | 1 |  | Device Type |
| 10 | `SEGMENT` | CHAR | 200 |  | Line Text 200 |
| 11 | `CUST_DATA` | CHAR | 200 |  | Line Text 200 |
