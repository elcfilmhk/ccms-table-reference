# ZISCS_USERPWD
**Description:** User ID and Password Table
**Total Fields:** 9
**Key Fields:** MANDT, USERID

## Programs Using This Table
- `ziscs0801`
- `ziscs0811`
- `ziscs0812`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `USERID` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 3 | `PASSWORD` | CHAR | 32 |  | Password |
| 4 | `LOCKUNLOCK` | CHAR | 1 |  | Lock Unlock Status |
| 5 | `COUNTER` | NUMC | 1 |  | Counter for wrong passwords |
| 6 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 7 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 8 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 9 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
