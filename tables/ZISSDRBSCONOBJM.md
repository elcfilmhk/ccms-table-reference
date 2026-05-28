# ZISSDRBSCONOBJM
**Description:** Bonus Scheme - Connection Object for Main Scheme
**Total Fields:** 6
**Key Fields:** MANDT, SCHEME, BONSC, HAUS

## Programs Using This Table
- `zissd00107`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHEME` | CHAR | 10 | 🔑 | Scheme |
| 3 | `BONSC` | CHAR | 10 | 🔑 | Scheme Type |
| 4 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 5 | `VLFRM` | DATS | 8 |  | Valid from (sub) |
| 6 | `VLTO` | DATS | 8 |  | Valid to (sub) |
