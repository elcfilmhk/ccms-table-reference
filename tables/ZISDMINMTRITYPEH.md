# ZISDMINMTRITYPEH
**Description:** Storing the changes of the Installation/Meter RI Type List
**Total Fields:** 9
**Key Fields:** MANDT, TYPE, VALUE, OLDVALUE, NEWVALUE, ACTION, CRTDATE, CRTTIME

## Programs Using This Table
- `zisdm0341`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 10 | 🔑 | Stores the action that has been taken |
| 3 | `VALUE` | CHAR | 18 | 🔑 | Stores the value of the data, i.e. Installation / Meter |
| 4 | `OLDVALUE` | CHAR | 18 | 🔑 | Stores the value of the data, i.e. Installation / Meter |
| 5 | `NEWVALUE` | CHAR | 18 | 🔑 | Stores the value of the data, i.e. Installation / Meter |
| 6 | `ACTION` | CHAR | 10 | 🔑 | Stores the action that has been taken |
| 7 | `CRTDATE` | DATS | 8 | 🔑 | Creation date |
| 8 | `CRTTIME` | TIMS | 6 | 🔑 | Time |
| 9 | `CRTUSER` | CHAR | 12 |  | User Name |
