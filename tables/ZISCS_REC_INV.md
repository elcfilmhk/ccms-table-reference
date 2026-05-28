# ZISCS_REC_INV
**Description:** Store the output for program ZISCS0508
**Total Fields:** 23
**Key Fields:** MANDT, REGEN_TYPE

## Programs Using This Table
- `ziscs0508`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REGEN_TYPE` | CHAR | 2 | 🔑 | Re Source |
| 3 | `HIST_2YR` | DEC | 12 |  | History generation |
| 4 | `HIST_1YR` | DEC | 12 |  | History generation |
| 5 | `HIST_CURR` | DEC | 12 |  | Current Year History Generation |
| 6 | `FORECAST_CURR` | DEC | 12 |  | Current Year Forecast Generation |
| 7 | `FORECAST_NEXT` | DEC | 12 |  | Next Year Forecast Generation |
| 8 | `TOTAL_QUOTA` | DEC | 12 |  | Total Quota Available |
| 9 | `BUFFER` | DEC | 12 |  | Buffer Quota |
| 10 | `TOT_QT_FOR_SALES` | DEC | 12 |  | Total Quantity for Sales |
| 11 | `TOT_CERT_SOLD2YR` | DEC | 12 |  | Total Units Sold by Certificate |
| 12 | `TOT_CERT_SOLD1YR` | DEC | 12 |  | Total Units Sold by Certificate |
| 13 | `TOT_CERT_SOLDCYR` | DEC | 12 |  | Total Units Sold by Certificate |
| 14 | `TOT_CERT_SOLDNYR` | DEC | 12 |  | Total Units Sold by Certificate |
| 15 | `TOT_CERT_SOLDOTH` | DEC | 12 |  | Total Units Sold by Certificate |
| 16 | `TOT_CERT_UNSOLD` | DEC | 12 |  | Total Re Certificate Reserved |
| 17 | `BAL_QT_SALES` | DEC | 12 |  | Balance Unit Available for Sales |
| 18 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 19 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 20 | `ERZET` | TIMS | 6 |  | Entry time |
| 21 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 22 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 23 | `AEZET` | TIMS | 6 |  | Time last change was made |
