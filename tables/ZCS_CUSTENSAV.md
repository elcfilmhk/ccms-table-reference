# ZCS_CUSTENSAV
**Description:** Structure for Energy Saving
**Total Fields:** 18
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0818`
- `ziscs0823`
- `ziscs0825`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROG_ID` | CHAR | 8 |  | Programme ID |
| 2 | `CANUMBER` | CHAR | 12 |  | Contract Account Number |
| 3 | `REG_ID` | CHAR | 10 |  | Registration ID |
| 4 | `BEGABRPE` | DATS | 8 |  | Start of billing period |
| 5 | `ENDABRPE` | DATS | 8 |  | End of billing period |
| 6 | `REG_DATE` | DATS | 8 |  | Registration Date |
| 7 | `REWARD_PROG` | CHAR | 1 |  | Reward Program joined |
| 8 | `TOTALCURRYEAR` | DEC | 16 |  | Current Year Cons. |
| 9 | `TOTALLASTYEAR` | DEC | 16 |  | Last Year Cons. |
| 10 | `TOTALCONS` | DEC | 16 |  | Cons.Saved |
| 11 | `ENERGYSAVING` | DEC | 16 |  | Cons. Change (%) |
| 12 | `ECO_POINT` | CHAR | 1 |  | ECO POINT |
| 13 | `CREATED_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `CREATED_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 15 | `CREATED_TIME` | TIMS | 6 |  | Time at which the object was created |
| 16 | `CHANGED_USER` | CHAR | 12 |  | Changed by |
| 17 | `CHANGED_DATE` | DATS | 8 |  | Last Changed On |
| 18 | `CHANGED_TIME` | TIMS | 6 |  | Time of Change |
