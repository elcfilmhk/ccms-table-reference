# ZISDMBCAS
**Description:** Contract for BCAS synchronization program
**Total Fields:** 5
**Key Fields:** MANDT, VERTRAG

## Programs Using This Table
- `zisdm0090`
- `zisdm0091`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 3 | `PID` | NUMC | 5 |  | 5 Character Numeric NUMC |
| 4 | `BILLCNT` | NUMC | 8 |  | Counter for number of premise ID |
| 5 | `ZZAVG` | NUMC | 8 |  | Average Number |
