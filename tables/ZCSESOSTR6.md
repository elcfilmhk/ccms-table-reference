# ZCSESOSTR6
**Description:** Output Structure for Z_ISDCS_RETRIEVE_ESERVICE_DTL.
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERVTYPE` | CHAR | 1 |  | Type of eService |
| 2 | `STATUS` | CHAR | 1 |  | Status |
| 3 | `DETAIL` | CHAR | 10 |  | Details of the eService type |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Create By |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Change By |
