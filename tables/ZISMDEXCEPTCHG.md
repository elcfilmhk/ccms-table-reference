# ZISMDEXCEPTCHG
**Description:** Storing the changes of the Meter Exception List
**Total Fields:** 8
**Key Fields:** MANDT, TYPE, OLDVALUE, NEWVALUE, ACTION, CRTDATE, CRTTIME

## Programs Using This Table
- `zisdm0184`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 1 | 🔑 | Specifies the type of the value store in ZISMDEXCEPT |
| 3 | `OLDVALUE` | CHAR | 18 | 🔑 | Stores the value of the data, i.e. Installation / Meter |
| 4 | `NEWVALUE` | CHAR | 18 | 🔑 | Stores the value of the data, i.e. Installation / Meter |
| 5 | `ACTION` | CHAR | 10 | 🔑 | Stores the action that has been taken |
| 6 | `CRTDATE` | DATS | 8 | 🔑 | Creation date |
| 7 | `CRTTIME` | TIMS | 6 | 🔑 | Time |
| 8 | `CRTUSER` | CHAR | 12 |  | User Name |
