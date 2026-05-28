# ZISDMZECON
**Description:** Customized table for zero consumption
**Total Fields:** 10
**Key Fields:** MANDT, TARIFTYP

## Programs Using This Table
- `zisdm0035`
- `zisdm0072`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `TL1_DAYS` | NUMC | 3 |  | Interval days for zero consumption |
| 4 | `TL1_FLAG` | CHAR | 1 |  | Indicator for check /read |
| 5 | `TL1_AUFART` | CHAR | 4 |  | Order Type |
| 6 | `TL1_ILART` | CHAR | 3 |  | Maintenance activity type |
| 7 | `TL2_DAYS` | NUMC | 3 |  | Interval days for zero consumption |
| 8 | `TL2_FLAG` | CHAR | 1 |  | Indicator for check /read |
| 9 | `TL2_AUFART` | CHAR | 4 |  | Order Type |
| 10 | `TL2_ILART` | CHAR | 3 |  | Maintenance activity type |
