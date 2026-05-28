# ZISDMCONSG
**Description:** EDM19 - Consumption Group Indicator Table
**Total Fields:** 5
**Key Fields:** MANDT, ZPRIO

## Programs Using This Table
- `ziscs0014`
- `ziscs0014_adj`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZPRIO` | CHAR | 2 | 🔑 | Priority |
| 3 | `ZLOWER` | DEC | 16 |  | Lower Value |
| 4 | `ZUPPER` | DEC | 16 |  | Upper Value |
| 5 | `ZCONSUM` | CHAR | 40 |  | Consumption |
