# ZISCSEWMSHIS
**Description:** Service Order History Table - EWMS
**Total Fields:** 9
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0002`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `SECNAM` | CHAR | 12 |  | Second last changed by |
| 4 | `SECDAT` | DATS | 8 |  | Second last change date |
| 5 | `SECEWMS` | CHAR | 1 |  | Changed by EWMS |
| 6 | `AENAM` | CHAR | 12 |  | Last changed by |
| 7 | `AEDAT` | DATS | 8 |  | Change date for Order Master |
| 8 | `AEZEIT` | TIMS | 6 |  | Changed at |
| 9 | `AEEWMS` | CHAR | 1 |  | Changed by EWMS |
