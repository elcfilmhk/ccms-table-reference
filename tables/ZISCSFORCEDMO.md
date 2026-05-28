# ZISCSFORCEDMO
**Description:** Forced Move-Out Cases
**Total Fields:** 5
**Key Fields:** MANDT, ACCT

## Programs Using This Table
- `ziscs0256`
- `ziscs0297`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `MO_DATE` | DATS | 8 |  | Move-Out Date |
| 4 | `CREATE_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `CREATE_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
