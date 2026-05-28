# ZISDMCPCPROCESS
**Description:** Periodic Consumption Update
**Total Fields:** 6
**Key Fields:** MANDT, ANLAGE, SERNR

## Programs Using This Table
- `zisdm0258`
- `zisdm0258_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Device |
| 4 | `PID` | NUMC | 5 |  | Process ID |
| 5 | `PROCESSED` | CHAR | 1 |  | Processed |
| 6 | `ERROR_MSG` | CHAR | 100 |  | Error Message |
