# ZISBIBBEPREI
**Description:** Budget billing rate change table
**Total Fields:** 5
**Key Fields:** MANDT, TARIFTYP, BIS

## Programs Using This Table
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `BIS` | DATS | 8 | 🔑 | Date at Which a Time Slice Expires |
| 4 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 5 | `PRICE_AMT` | DEC | 17 |  | Price amount |
