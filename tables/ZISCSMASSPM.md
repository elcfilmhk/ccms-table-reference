# ZISCSMASSPM
**Description:** Mass update premises
**Total Fields:** 4
**Key Fields:** MANDT, VSTELLE, FLAECHE, TIMESTAMP

## Programs Using This Table
- `ziscs0234`
- `ziscs0236`
- `ziscs0249`
- `ziscs0250`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `FLAECHE` | CHAR | 15 | 🔑 | Char 15 |
| 4 | `TIMESTAMP` | DEC | 15 | 🔑 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
