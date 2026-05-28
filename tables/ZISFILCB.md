# ZISFILCB
**Description:** Pay type for lockbox batch file
**Total Fields:** 3
**Key Fields:** MANDT, ZZPAYTYPE

## Programs Using This Table
- `zisfi0013`
- `zisfi0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZPAYTYPE` | NUMC | 2 | 🔑 | Pay Type code for SCB Lockbox |
| 3 | `ZZDESC` | CHAR | 30 |  | Pay Type Description |
