# ZBACBFIELD
**Description:** BDC session create: Screen field table
**Total Fields:** 20
**Key Fields:** GROUPID, VERSION, SCREENO, FIELDNO

## Programs Using This Table
- `zbacbe005`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `GROUPID` | CHAR | 12 | 🔑 | Group name: Batch input session name |
| 2 | `VERSION` | NUMC | 4 | 🔑 | Count parameters |
| 3 | `SCREENO` | NUMC | 4 | 🔑 | Count parameters |
| 4 | `FIELDNO` | NUMC | 4 | 🔑 | Count parameters |
| 5 | `PROCESS` | CHAR | 1 |  | Process type for BDC session |
| 6 | `.INCLUDE` | &nbsp; | 0 |  | BDC: Substitute for FIELD_VALS because of field active |
| 7 | `FIELDNAME` | CHAR | 132 |  | BDC field name |
| 8 | `STEPL` | INT4 | 10 |  | Index of Current Step Loop Line |
| 9 | `FIELDVALUE` | CHAR | 132 |  | BDC field value |
| 10 | `INPUT_OFF` | CHAR | 1 |  | CHAR01 data element for SYST |
| 11 | `SUPPRESS` | CHAR | 1 |  | CHAR01 data element for SYST |
| 12 | `NR_DYNPRO` | NUMC | 4 |  | NUM04 for SYST |
| 13 | `.INCLUDE` | &nbsp; | 0 |  | BDC session: data for KSM processing |
| 14 | `FIRMA` | CHAR | 5 |  | Company (Client) for Migration |
| 15 | `OBJECT` | CHAR | 10 |  | Migration Object |
| 16 | `.INCLUDE` | &nbsp; | 0 |  | BDC: Statistik structure BDC objects |
| 17 | `DATUM` | DATS | 8 |  | Date |
| 18 | `UZEIT` | TIMS | 6 |  | Time |
| 19 | `UNAME` | CHAR | 12 |  | User Name |
| 20 | `ACTIVE` | CHAR | 1 |  | Element is active |
