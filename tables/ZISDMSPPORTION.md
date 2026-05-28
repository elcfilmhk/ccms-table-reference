# ZISDMSPPORTION
**Description:** Store the special portion ID assignment record
**Total Fields:** 4
**Key Fields:** MANDT, ADATSOLL, ANLAGE

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`
- `zisdm0193`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `PORTION` | CHAR | 8 |  | Portion |
