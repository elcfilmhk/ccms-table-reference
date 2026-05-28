# ZCS_UPDMKT_LOG
**Description:** Update Marketing Consent Log
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, TIMESTAMP

## Programs Using This Table
- `ziscs0256`
- `ziscs1135`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TIMESTAMP` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 5 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 6 | `MKT_EMAIL` | CHAR | 60 |  | Marketing  Email |
| 7 | `MKT_PHONE` | CHAR | 10 |  | Marketing Phone |
| 8 | `STATUS` | CHAR | 1 |  | Status |
| 9 | `STEP` | NUMC | 2 |  | Step |
| 10 | `ZCOUNT` | NUMC | 3 |  | Counter |
| 11 | `MESSAGE` | CHAR | 220 |  | Message Text |
