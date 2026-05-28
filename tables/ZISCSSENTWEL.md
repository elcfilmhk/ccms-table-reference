# ZISCSSENTWEL
**Description:** Send welcome email for WebService account
**Total Fields:** 7
**Key Fields:** MANDT, CTR_ACC_ID

## Programs Using This Table
- `ziscs0245`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CTR_ACC_ID` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 5 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 6 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 7 | `WELSENT` | CHAR | 1 |  | Welcome email sent |
