# ZISDMIVLOG
**Description:** Temporary Log of IV61-IV65 for batch run
**Total Fields:** 10
**Key Fields:** MANDT, RUNDT, ABLBELNR

## Programs Using This Table
- `zisdm0040`
- `zisdm0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Date |
| 3 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 4 | `GERNR` | CHAR | 18 |  | Device |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `ABLSTAT` | CHAR | 1 |  | Meter Reading Status |
| 7 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 8 | `PRUEFPKT` | CHAR | 2 |  | Independent validation |
| 9 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 10 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |
