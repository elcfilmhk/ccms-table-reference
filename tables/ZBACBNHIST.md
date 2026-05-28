# ZBACBNHIST
**Description:** NRO: History of buffer settings
**Total Fields:** 10
**Key Fields:** OBJECT, VERSION

## Programs Using This Table
- `zbacbe016`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `OBJECT` | CHAR | 10 | 🔑 | Name of number range object |
| 2 | `VERSION` | NUMC | 4 | 🔑 | Count parameters |
| 3 | `BUFFER` | CHAR | 1 |  | Buffer flag |
| 4 | `NOIVBUFFER` | NUMC | 8 |  | No. of numbers that must be held in the buffer |
| 5 | `NONRSWAP` | CHAR | 1 |  | Flag: No rolling of intervals |
| 6 | `.INCLUDE` | &nbsp; | 0 |  | Conversion: Statistik structure scheduling objects |
| 7 | `DATUM` | DATS | 8 |  | Date |
| 8 | `UZEIT` | TIMS | 6 |  | Time |
| 9 | `UNAME` | CHAR | 12 |  | User Name |
| 10 | `ACTIVE` | CHAR | 1 |  | Element is active |
