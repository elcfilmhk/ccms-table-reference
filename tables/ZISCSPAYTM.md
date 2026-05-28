# ZISCSPAYTM
**Description:** Payment Terms and Alternate Portion mapping
**Total Fields:** 3
**Key Fields:** MANDT, PORTION, ZAHLKOND

## Programs Using This Table
- `zisbi0049`
- `ziscs0246`
- `ziscs0247`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PORTION` | CHAR | 8 | 🔑 | Alternative portion |
| 3 | `ZAHLKOND` | CHAR | 4 | 🔑 | Payment Condition |
