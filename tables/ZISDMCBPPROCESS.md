# ZISDMCBPPROCESS
**Description:** Installation for change base period process
**Total Fields:** 6
**Key Fields:** MANDT, ANLAGE

## Programs Using This Table
- `zisdm0256`
- `zisdm0256_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `BAPERTYP` | CHAR | 1 |  | Base period category |
| 4 | `PID` | NUMC | 5 |  | Process ID |
| 5 | `PROCESSED` | CHAR | 1 |  | Character Field Length 1 |
| 6 | `ERROR_MSG` | CHAR | 100 |  | Character 100 |
