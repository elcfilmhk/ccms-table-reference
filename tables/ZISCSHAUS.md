# ZISCSHAUS
**Description:** Custom table Connection Object for CSPS
**Total Fields:** 9
**Key Fields:** MANDT, HAUS, PID

## Programs Using This Table
- `ziscs0048`
- `ziscs0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HAUS` | CHAR | 30 | 🔑 | Connection Object |
| 3 | `PID` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `VSTELLE_NO` | NUMC | 10 |  | Numeric Character Field, Length 10 |
| 5 | `VERTRAG_NO` | NUMC | 10 |  | Numeric Character Field, Length 10 |
| 6 | `GERNR_NO` | NUMC | 10 |  | Numeric Character Field, Length 10 |
| 7 | `ZZNEW` | CHAR | 1 |  | Single-Character Flag |
| 8 | `VSTCNT` | NUMC | 8 |  | Counter for number of premise ID |
| 9 | `ZZAVG` | NUMC | 8 |  | Average Number |
