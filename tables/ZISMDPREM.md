# ZISMDPREM
**Description:** Store the premise that have channeled to MDMS from CCMS
**Total Fields:** 3
**Key Fields:** MANDT, VSTELLE

## Programs Using This Table
- `zismd0001`
- `zismd0010`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `HAUS` | CHAR | 30 |  | Connection Object |
