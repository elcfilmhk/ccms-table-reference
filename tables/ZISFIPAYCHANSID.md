# ZISFIPAYCHANSID
**Description:** Mobile Payment Account Subscription
**Total Fields:** 10
**Key Fields:** MANDT, OFFIC_EX, VKONT, ZZSUBID

## Programs Using This Table
- `ziscs_migration_alipay_wechat`
- `zisfi0307`
- `zisfi0310a`
- `zisfi0310b`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ZZSUBID` | CHAR | 64 | 🔑 | Subscription ID |
| 5 | `ZZOPENID` | CHAR | 64 |  | Open ID |
| 6 | `ZZSTATUS_SID` | CHAR | 1 |  | Subscription Status |
| 7 | `ZZCHANGE_DATE` | DATS | 8 |  | Change Date |
| 8 | `ZZCHANGE_TIME` | TIMS | 6 |  | Change Time |
| 9 | `ZZCREATE_DATE` | DATS | 8 |  | Created on |
| 10 | `ZZCREATE_TIME` | TIMS | 6 |  | Time of creation |
