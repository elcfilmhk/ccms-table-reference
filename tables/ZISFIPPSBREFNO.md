# ZISFIPPSBREFNO
**Description:** PPSB REFERENCE NUMBER
**Total Fields:** 12
**Key Fields:** MANDT, ZZREFNO, VKONT

## Programs Using This Table
- `zisfi0280`
- `zisfi0281`
- `zisfi0318`
- `zisfi0324`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZREFNO` | CHAR | 16 | 🔑 | CLP Reference Number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ZZPPSBAMT` | CURR | 13 |  | Amount |
| 5 | `ZZSTATUSCOD` | CHAR | 2 |  | Status Code |
| 6 | `ZZDODATE` | DATS | 8 |  | Order Date |
| 7 | `ZZDOTIME` | TIMS | 6 |  | Order Time |
| 8 | `ZZDRDATE` | DATS | 8 |  | Receipt Date |
| 9 | `ZZDRTIME` | TIMS | 6 |  | Receipt Time |
| 10 | `ZZPAYTYPE` | CHAR | 1 |  | Pay Type |
| 11 | `ZZPYMTCHNL` | CHAR | 2 |  | Payment Channel |
| 12 | `ZZPPSREFNO` | CHAR | 16 |  | PPS Reference Number |
