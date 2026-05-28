# ZCS_SETALERT_LOG
**Description:** Turn on billing and payment related alerts Log(PRG-ZISCS113)
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, TIMESTAMP, ZZCSTYPE, CHANNEL

## Programs Using This Table
- `ziscs1136`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TIMESTAMP` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `ZZCSTYPE` | CHAR | 2 | 🔑 | Eservice typ E and 7 |
| 5 | `CHANNEL` | CHAR | 1 | 🔑 | Dispatch |
| 6 | `CIAMID` | CHAR | 50 |  | CIAM ID |
| 7 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 8 | `STATUS` | CHAR | 1 |  | Status |
| 9 | `MESSAGE` | CHAR | 220 |  | Message Text |
