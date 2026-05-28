# ZISCSINST
**Description:** Custom table for ICS01  - Meter Level
**Total Fields:** 7
**Key Fields:** MANDT, VSTELLE, GERNR, INSDATE, TIMESTAND

## Programs Using This Table
- `ziscs0048`
- `ziscs0049`
- `ziscs0068`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `GERNR` | CHAR | 8 | 🔑 | Character field, 8 characters long |
| 4 | `INSDATE` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 5 | `TIMESTAND` | CHAR | 12 | 🔑 | Character Field of Length 12 |
| 6 | `FUNKLAS` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 7 | `OPCODE` | CHAR | 1 |  | Single-Character Flag |
