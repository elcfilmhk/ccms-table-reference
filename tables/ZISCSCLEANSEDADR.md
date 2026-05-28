# ZISCSCLEANSEDADR
**Description:** CEP: Store the cleansed address
**Total Fields:** 10
**Key Fields:** MANDT, PREMISE_ID

## Programs Using This Table
- `ziscs0099`
- `ziscs0444`
- `ziscs0447`
- `ziscs0450`
- `ziscs_cleansed_adr============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PREMISE_ID` | CHAR | 10 | 🔑 | Premise id |
| 3 | `SVC_PREMISE` | CHAR | 100 |  | Premise |
| 4 | `SVC_STREET_NO` | CHAR | 100 |  | Street Number |
| 5 | `SVC_STREET` | CHAR | 100 |  | Street |
| 6 | `SVC_SUBPREMISE` | CHAR | 100 |  | Sub premise |
| 7 | `SVC_LOCALITY` | CHAR | 100 |  | District |
| 8 | `YEAR_BUILT` | CHAR | 10 |  | Character Field Length = 10 |
| 9 | `LATITUDE` | CHAR | 100 |  | Character 100 |
| 10 | `LONGITUDE` | CHAR | 100 |  | Character 100 |
