# ZISCSBPADD
**Description:** Process ID for Changed Supply Address
**Total Fields:** 8
**Key Fields:** MANDT, HAUS, VSTELLE, ADRNR, VKONT

## Programs Using This Table
- `ziscs0100`
- `ziscs0105`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 3 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 4 | `ADRNR` | CHAR | 10 | 🔑 | Address |
| 5 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 7 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 8 | `PID2` | NUMC | 5 |  | Process ID |
