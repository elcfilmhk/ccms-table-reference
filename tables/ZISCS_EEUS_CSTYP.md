# ZISCS_EEUS_CSTYP
**Description:** EEUS Customer Type
**Total Fields:** 8
**Key Fields:** MANDT, ELIG_CUST_TYPE, RATE_CAT

## Programs Using This Table
- `ziscs0524`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ELIG_CUST_TYPE` | CHAR | 1 | 🔑 | Eligible Customer Type |
| 3 | `RATE_CAT` | CHAR | 10 | 🔑 | Rate category |
| 4 | `CAN_NO_CONTACT` | CHAR | 2 |  | Maxi no of Cannot be contacted |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
