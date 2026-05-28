# ZISCSPREMI
**Description:** Process ID for Changed Supply Address
**Total Fields:** 5
**Key Fields:** MANDT, HAUS, VSTELLE, ADRNR, PID

## Programs Using This Table
- `ziscs0093`
- `ziscs0100`
- `ziscs0105`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 3 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 4 | `ADRNR` | CHAR | 10 | 🔑 | Address |
| 5 | `PID` | NUMC | 5 | 🔑 | Process ID |
