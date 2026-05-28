# ZISDMMESSG
**Description:** Message table for RMTM (HKVA, Low Consumption)
**Total Fields:** 9
**Key Fields:** MANDT, RPT_TYPE, TYPE, AUFNR, TPLNR

## Programs Using This Table
- `zisdm0035`
- `zisdm0065`
- `zisdm0067`
- `zisdm0068`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPT_TYPE` | CHAR | 4 | 🔑 | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 4 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 5 | `TPLNR` | CHAR | 30 | 🔑 | Functional Location |
| 6 | `MESSAGE` | CHAR | 220 |  | Message Text |
| 7 | `MESSAGE_V1` | CHAR | 50 |  | Message Variable |
| 8 | `MESSAGE_V2` | CHAR | 50 |  | Message Variable |
| 9 | `MESSAGE_V3` | CHAR | 50 |  | Message Variable |
