# ZISBIPROCEVER
**Description:** Contract to be processed by background task
**Total Fields:** 3
**Key Fields:** MANDT, VERTRAG

## Programs Using This Table
- `zisbi0168`
- `zisbi0169`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 3 | `ABRSPERR` | CHAR | 2 |  | Reason for blocking billing |
