# ZISFICHANNEL_FEE
**Description:** Payment Channel Fee for Payment
**Total Fields:** 4
**Key Fields:** MANDT, PAYT_CHANNEL, EFFDATE

## Programs Using This Table
- `zisfi0003`
- `zisfi0144`
- `zisfi0174`
- `zisfi0311b`
- `zisfi0312`
- `zisfi0318`
- `zisfi0323`
- `zisfi0334`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PAYT_CHANNEL` | CHAR | 10 | 🔑 | Payment Channel |
| 3 | `EFFDATE` | DATS | 8 | 🔑 | Effective From |
| 4 | `FEE` | CURR | 13 |  | Channel Fee |
