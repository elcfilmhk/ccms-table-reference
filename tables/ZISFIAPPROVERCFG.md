# ZISFIAPPROVERCFG
**Description:** Approver Configuration Table for Credit Control Workflow
**Total Fields:** 11
**Key Fields:** MANDT, ZZKEY, ZZTYPES, ZZLEVEL, ZZPOSITION

## Programs Using This Table
- `zisfi0098`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZKEY` | CHAR | 7 | 🔑 | Transaction Key |
| 3 | `ZZTYPES` | CHAR | 1 | 🔑 | Transaction Type |
| 4 | `ZZLEVEL` | NUMC | 4 | 🔑 | Approving Level |
| 5 | `ZZPOSITION` | NUMC | 8 | 🔑 | Position |
| 6 | `ZZAMOUNTFROM` | CURR | 13 |  | Amount From |
| 7 | `ZZAMOUNTTO` | CURR | 13 |  | Amount To |
| 8 | `WAERS` | CUKY | 5 |  | Currency Key |
| 9 | `ZZPERIODFROM` | NUMC | 4 |  | Period From |
| 10 | `ZZPERIODTO` | NUMC | 4 |  | Period To |
| 11 | `ZZSIGN` | CHAR | 3 |  | Logical Sign |
