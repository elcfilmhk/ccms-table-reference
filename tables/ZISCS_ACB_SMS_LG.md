# ZISCS_ACB_SMS_LG
**Description:** Log table for program ZISCS0408
**Total Fields:** 10
**Key Fields:** MANDT, RUN_DT, BATCH_ID, SMS, VKONT

## Programs Using This Table
- `ziscs0408`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUN_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `BATCH_ID` | CHAR | 32 | 🔑 | GUID in 'CHAR' Format in Uppercase |
| 4 | `SMS` | CHAR | 50 | 🔑 | Attribute 1 for Contact Information |
| 5 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `LANG` | CHAR | 1 |  | CEP: Home Energy Report (HER) Language |
| 7 | `SMS_ID` | CHAR | 32 |  | GUID in 'CHAR' Format in Uppercase |
| 8 | `SUCC_FAIL` | CHAR | 1 |  | Single-Character Flag |
| 9 | `RETURN_CODE` | CHAR | 100 |  | Return Code |
| 10 | `RETURN_MSG` | CHAR | 220 |  | Message Text |
