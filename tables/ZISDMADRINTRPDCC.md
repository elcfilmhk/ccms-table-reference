# ZISDMADRINTRPDCC
**Description:** ADR Customer incentive rate
**Total Fields:** 8
**Key Fields:** MANDT, DRCUSTNO, RATETYPE

## Programs Using This Table
- `zisdm0309`
- `zisdm0313_adr`
- `zisdm0314_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DRCUSTNO` | CHAR | 80 | 🔑 | DR Customer Number |
| 3 | `RATETYPE` | CHAR | 20 | 🔑 | Incentive Rate Type |
| 4 | `RATE` | DEC | 16 |  | Unit Rate |
| 5 | `UNIT` | CHAR | 10 |  | Incentive Rate Unit |
| 6 | `ACTION` | CHAR | 1 |  | DR Customer information update type method |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
