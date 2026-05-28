# ZISCEPSPSUBPREM
**Description:** CEP: Store Masked Sub Premise for Service point
**Total Fields:** 4
**Key Fields:** MANDT, VSTELLE

## Programs Using This Table
- `ziscs0354`
- `ziscs0444`
- `ziscs0451`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `MASKED_PREMISE` | CHAR | 40 |  | Character field of length 40 |
| 4 | `MASKED_SUBPREM` | CHAR | 100 |  | Character 100 |
