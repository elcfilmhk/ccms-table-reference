# ZISDMBILLBLKREG
**Description:** Billing Block Register
**Total Fields:** 7
**Key Fields:** MANDT, CASE_NR, ABLBELNR

## Programs Using This Table
- `zisdm0050`
- `zisdm0392`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CASE_NR` | CHAR | 10 | 🔑 | Change Number of Document |
| 3 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 4 | `GERNR` | CHAR | 18 |  | Device |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `PROCESSED` | CHAR | 1 |  | Checkbox |
