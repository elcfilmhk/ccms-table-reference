# ZEEUSVALTAB7
**Description:** Maintain Customer type
**Total Fields:** 7
**Key Fields:** MANDT, ELIG_CUST_TYPE

## Programs Using This Table
- `ziscs0722b`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ELIG_CUST_TYPE` | CHAR | 1 | 🔑 | Eligible Customer Type |
| 3 | `CUST_TY_DESC` | CHAR | 20 |  | Description of Customer type |
| 4 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 7 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
