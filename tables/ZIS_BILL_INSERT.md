# ZIS_BILL_INSERT
**Description:** Get Bill Insert
**Total Fields:** 4
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0268`
- `ziscs0715`
- `ziscs1138`
- `ziscs1139`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `SPOOL` | INT4 | 10 |  | Spool request number |
