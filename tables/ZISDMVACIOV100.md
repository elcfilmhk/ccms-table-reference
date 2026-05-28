# ZISDMVACIOV100
**Description:** Vacant installation with consumption after move-out over 100
**Total Fields:** 5
**Key Fields:** MANDT, ANLAGE, AUSZBELEG, AUSZDAT, VSTELLE

## Programs Using This Table
- `zisdm0190`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `AUSZBELEG` | CHAR | 12 | 🔑 | Consecutive number of move-out document |
| 4 | `AUSZDAT` | DATS | 8 | 🔑 | Move-Out Date |
| 5 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
