# ZISCSICS27
**Description:** Reject reason for Mass Move In
**Total Fields:** 4
**Key Fields:** MANDT, ZZREJCODE

## Programs Using This Table
- `ziscs0023`
- `ziscs0028`
- `ziscs0207`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZREJCODE` | CHAR | 3 | 🔑 | Reject reason code |
| 3 | `ZZREPTSEQ` | CHAR | 2 |  | Reporting sequence |
| 4 | `ZZREJMESG` | CHAR | 50 |  | Reject message |
