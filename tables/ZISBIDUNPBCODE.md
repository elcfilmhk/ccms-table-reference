# ZISBIDUNPBCODE
**Description:** Postman Beat Code for Postal Address (Dunning)
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, ADDRNUMBER

## Programs Using This Table
- `zisbi0076`
- `zisbi0098`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ADDRNUMBER` | CHAR | 10 | 🔑 | Address Number |
| 4 | `DOCODE` | CHAR | 3 |  | District Office Code (obsolete) |
| 5 | `PBCODE` | CHAR | 12 |  | Postman Beat Code (obsolete) |
| 6 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 7 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 8 | `TIMES` | TIMS | 6 |  | Time when the record was created |
