# ZISCSCOMCND_CFG
**Description:** Communication Condition Config Table
**Total Fields:** 5
**Key Fields:** MANDT, MESSAGETYPE

## Programs Using This Table
- `ziscrm0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MESSAGETYPE` | CHAR | 2 | 🔑 | Message Type |
| 3 | `EMAIL_PRIORITY` | CHAR | 1 |  | Email priority |
| 4 | `SMS_PRIORITY` | CHAR | 1 |  | SMS Priority |
| 5 | `MOBILEPUSH_PRIORITY` | CHAR | 1 |  | Mobile Push Priority |
