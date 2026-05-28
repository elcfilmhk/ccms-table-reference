# ZISDMPCIDS
**Description:** PC Name State information
**Total Fields:** 3
**Key Fields:** MANDT, DWNLFILE

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DWNLFILE` | CHAR | 10 | 🔑 | Streetwise Download filename by PC ID |
| 3 | `ALLMRU` | CHAR | 1 |  | Indicate that this PC refers to ALL MRUs |
