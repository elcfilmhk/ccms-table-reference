# ZISCSMASSCO
**Description:** Mass update connection object
**Total Fields:** 4
**Key Fields:** MANDT, HAUS, BAUJJ, TIMESTAMP

## Programs Using This Table
- `ziscs0233`
- `ziscs0235`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 3 | `BAUJJ` | CHAR | 4 | 🔑 | Year of construction |
| 4 | `TIMESTAMP` | DEC | 15 | 🔑 | UTC Time Stamp in Short Form (YYYYMMDDhhmmss) |
