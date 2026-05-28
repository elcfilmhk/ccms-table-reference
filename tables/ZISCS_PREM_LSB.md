# ZISCS_PREM_LSB
**Description:** Premise supplementary info
**Total Fields:** 26
**Key Fields:** MANDT, PREMISE_ID

## Programs Using This Table
- `ziscs0384_eec`
- `ziscs0385_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PREMISE_ID` | CHAR | 10 | 🔑 | Premise |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 5 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 6 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 7 | `STR_ERG2` | CHAR | 40 |  | Street 3 |
| 8 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 9 | `STREET` | CHAR | 60 |  | Street |
| 10 | `CITY2` | CHAR | 40 |  | District |
| 11 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 12 | `LSB` | CHAR | 40 |  | LSB for EE&C Benchmark grouping |
| 13 | `LATITUDE` | CHAR | 100 |  | Character 100 |
| 14 | `LONGITUDE` | CHAR | 100 |  | Character 100 |
| 15 | `SVC_PREMISE` | CHAR | 100 |  | Premise |
| 16 | `SVC_STREET_NO` | CHAR | 100 |  | Street Number |
| 17 | `SVC_STREET` | CHAR | 100 |  | Street |
| 18 | `SVC_SUBPREMISE` | CHAR | 100 |  | Sub premise |
| 19 | `SVC_LOCALITY` | CHAR | 100 |  | District |
| 20 | `YEAR_BUILT` | CHAR | 10 |  | Character Field Length = 10 |
| 21 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 22 | `SVC_BUILDING1` | CHAR | 40 |  | Building 1 |
| 23 | `SVC_BUILDING2` | CHAR | 40 |  | Building 2 |
| 24 | `SVC_PHASE1` | CHAR | 20 |  | Phase 1 |
| 25 | `SVC_PHASE2` | CHAR | 20 |  | Phase 2 |
| 26 | `SVC_ESTATE` | CHAR | 20 |  | Estate |
