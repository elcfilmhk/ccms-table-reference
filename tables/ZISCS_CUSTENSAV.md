# ZISCS_CUSTENSAV
**Description:** Customer Energy Saving Details for Bi-Monthly Energy Saving
**Total Fields:** 19
**Key Fields:** MANDT, PROG_ID, CANUMBER, REG_ID, BEGABRPE, ENDABRPE

## Programs Using This Table
- `ziscs0818`
- `ziscs0820`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `CANUMBER` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `REG_ID` | CHAR | 10 | 🔑 | Registration ID |
| 5 | `BEGABRPE` | DATS | 8 | 🔑 | Start of billing period |
| 6 | `ENDABRPE` | DATS | 8 | 🔑 | End of billing period |
| 7 | `REG_DATE` | DATS | 8 |  | Registration Date |
| 8 | `REWARD_PROG` | CHAR | 1 |  | Reward Program joined |
| 9 | `ADCCURRYEAR` | DEC | 16 |  | ADC Current year |
| 10 | `ADCLASTYEAR` | DEC | 16 |  | ADC Last year |
| 11 | `AVGDAILYCONS` | DEC | 16 |  | ADC Cur year - ADC Last year |
| 12 | `ENERGYSAVING` | DEC | 16 |  | Cons. Change (%) |
| 13 | `ECO_POINT` | CHAR | 1 |  | ECO POINT |
| 14 | `CREATED_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 15 | `CREATED_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 16 | `CREATED_TIME` | TIMS | 6 |  | Time at which the object was created |
| 17 | `CHANGED_USER` | CHAR | 12 |  | Changed by |
| 18 | `CHANGED_DATE` | DATS | 8 |  | Last Changed On |
| 19 | `CHANGED_TIME` | TIMS | 6 |  | Time of Change |
