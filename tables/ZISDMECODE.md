# ZISDMECODE
**Description:** Error Code table for Streetwise Export
**Total Fields:** 3
**Key Fields:** MANDT, ZZERRCODE

## Programs Using This Table
- `zisdh0004`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0051`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZERRCODE` | CHAR | 2 | 🔑 | Error Code |
| 3 | `ZZERRDESC` | CHAR | 50 |  | Error Description |
