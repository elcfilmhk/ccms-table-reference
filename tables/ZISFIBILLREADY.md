# ZISFIBILLREADY
**Description:** Bill Ready to be Push Record
**Total Fields:** 7
**Key Fields:** MANDT, ZZPUSHDT, OFFIC_EX, ZZSUBID

## Programs Using This Table
- `zisfi0310a`
- `zisfi0310b`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZPUSHDT` | DATS | 8 | 🔑 | Date for Bill Ready to be Push |
| 3 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 4 | `ZZSUBID` | CHAR | 64 | 🔑 | Subscription ID |
| 5 | `ZZSUCCESS` | CHAR | 1 |  | Result of Push by Vendor |
| 6 | `ZZDBTDT` | DATS | 8 |  | Debit Date |
| 7 | `ZZREPDT` | DATS | 8 |  | Actual Push Date |
