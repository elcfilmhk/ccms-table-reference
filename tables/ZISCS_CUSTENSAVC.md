# ZISCS_CUSTENSAVC
**Description:** Customer Energy Saving Details for Annual Energy Saving
**Total Fields:** 21
**Key Fields:** MANDT, PROG_ID, CANUMBER, REG_ID, BEGABRPE, ENDABRPE

## Programs Using This Table
- `ziscs0825`
- `ziscs0827`

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
| 9 | `TOTALCURRYEAR` | DEC | 16 |  | Current Year Cons. |
| 10 | `TOTALLASTYEAR` | DEC | 16 |  | Last Year Cons. |
| 11 | `TOTALCONS` | DEC | 16 |  | Cons.Saved |
| 12 | `ENERGYSAVING` | DEC | 16 |  | Cons. Change (%) |
| 13 | `STAFF` | CHAR | 1 |  | STAFF |
| 14 | `E_COUPON` | CHAR | 1 |  | E Coupon |
| 15 | `REWARD_STATUS` | CHAR | 10 |  | Reward Status |
| 16 | `CREATED_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 17 | `CREATED_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 18 | `CREATED_TIME` | TIMS | 6 |  | Time at which the object was created |
| 19 | `CHANGED_USER` | CHAR | 12 |  | Changed by |
| 20 | `CHANGED_DATE` | DATS | 8 |  | Last Changed On |
| 21 | `CHANGED_TIME` | TIMS | 6 |  | Time of Change |
