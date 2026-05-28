# ZISDMRREAD
**Description:** Customized table for Re-read order
**Total Fields:** 7
**Key Fields:** MANDT, GERNR

## Programs Using This Table
- `zisdm0035`
- `zisdm0050`
- `zisdm0051`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ZZORGADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 4 | `ZZORDERERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 7 | `ABRDATS` | DATS | 8 |  | Scheduled Billing Date |
