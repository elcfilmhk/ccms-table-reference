# ZISMDCHGHAUS
**Description:** Connection Object Change Log
**Total Fields:** 5
**Key Fields:** MANDT, DATUM, UZEIT, TCODE, HAUS

## Programs Using This Table
- `zismd0001`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATUM` | DATS | 8 | 🔑 | System Date |
| 3 | `UZEIT` | TIMS | 6 | 🔑 | System Time |
| 4 | `TCODE` | CHAR | 20 | 🔑 | Transaction Code |
| 5 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
