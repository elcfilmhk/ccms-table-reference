# ZISCSCLTYP
**Description:** Custom table for call type
**Total Fields:** 6
**Key Fields:** MANDT, ZZCALLCODE

## Programs Using This Table
- `ziscs0111`
- `ziscs0119`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZCALLCODE` | CHAR | 4 | 🔑 | Call Type Code |
| 3 | `ZZCALLTYPE` | CHAR | 20 |  | Call Type |
| 4 | `ZZSUBCALL1` | CHAR | 30 |  | Sub Call Type 1 |
| 5 | `ZZSUBCALL2` | CHAR | 30 |  | Sub Call Type 2 |
| 6 | `ZZNUMCODE` | NUMC | 10 |  | Call Code (Numeric) |
