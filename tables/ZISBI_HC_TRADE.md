# ZISBI_HC_TRADE
**Description:** High consumption alert trade group
**Total Fields:** 4
**Key Fields:** MANDT, TRADE_GRP, KTOKL

## Programs Using This Table
- `zisbi0194`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRADE_GRP` | CHAR | 6 | 🔑 | High consumption trade group |
| 3 | `KTOKL` | CHAR | 4 | 🔑 | Account class |
| 4 | `TRADE_DESC` | CHAR | 50 |  | Description |
