# ZBACBBTCOD
**Description:** BDC session create: TCODE table
**Total Fields:** 14
**Key Fields:** GROUPID, VERSION

## Programs Using This Table
- `zbacbe006`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `GROUPID` | CHAR | 12 | 🔑 | Group name: Batch input session name |
| 2 | `VERSION` | NUMC | 4 | 🔑 | Count parameters |
| 3 | `.INCLUDE` | &nbsp; | 0 |  | BDC: Substitute for BDCTH, because of field print |
| 4 | `MTYPE` | CHAR | 1 |  | BDC message type |
| 5 | `STATE` | CHAR | 1 |  | BDC   status |
| 6 | `TCODE` | CHAR | 20 |  | BDC Transaction code |
| 7 | `POSTG` | CHAR | 1 |  | CALL TRANSACTION USING - processing mode (A, E, N) |
| 8 | `DRUCK` | CHAR | 1 |  | CALL TRANSACTION USING - processing mode (A, E, N) |
| 9 | `RESER` | CHAR | 20 |  | Batch input message ID |
| 10 | `.INCLUDE` | &nbsp; | 0 |  | BDC: Statistik structure BDC objects |
| 11 | `DATUM` | DATS | 8 |  | Date |
| 12 | `UZEIT` | TIMS | 6 |  | Time |
| 13 | `UNAME` | CHAR | 12 |  | User Name |
| 14 | `ACTIVE` | CHAR | 1 |  | Element is active |
