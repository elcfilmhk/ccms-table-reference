# ZISFIGLITEM
**Description:** Posting Request GL Portion
**Total Fields:** 7
**Key Fields:** MANDT, ZZREBATE_REF, ZZSEQNO

## Programs Using This Table
- `zisfi0138`
- `zisfi0168`
- `zisfi0197`
- `zisfi0197_smis`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZREBATE_REF` | CHAR | 16 | 🔑 | Rebate reference |
| 3 | `ZZSEQNO` | NUMC | 4 | 🔑 | Sequence Num. |
| 4 | `HKONT` | CHAR | 10 |  | General ledger account |
| 5 | `GSBER` | CHAR | 4 |  | Business Area |
| 6 | `KOSTL` | CHAR | 10 |  | Cost Center |
| 7 | `ZZPOST_RATIO` | CURR | 5 |  | Posting Ratio |
