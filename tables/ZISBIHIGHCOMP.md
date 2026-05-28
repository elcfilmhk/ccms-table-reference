# ZISBIHIGHCOMP
**Description:** High consumption alert log table
**Total Fields:** 26
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0147`
- `zisbi0152`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 6 | `MSGTYPE` | NUMC | 10 |  | Message number |
| 7 | `CY_CUR_AB` | DATS | 8 |  | Current Year Current Billing Period From Date (CB From) |
| 8 | `CY_CUR_BIS` | DATS | 8 |  | Current Year Current Billing Period To Date (CB To) |
| 9 | `CY_CUR_AVG_COMP` | DEC | 16 |  | Current Year Current BP Average Consumption (CB Comp) |
| 10 | `CY_PREV_AB` | DATS | 8 |  | Current Year Previous Billing Period From Date (PB From) |
| 11 | `CY_PREV_BIS` | DATS | 8 |  | Current Year Previous Billing Period To Date (PB To) |
| 12 | `CY_PREV_AVG_COMP` | DEC | 16 |  | Current Year Previous BP Average Consumption (PB Comp) |
| 13 | `PY_CUR_AB` | DATS | 8 |  | Previous Year Current Billing Period From Date (PY CB From) |
| 14 | `PY_CUR_BIS` | DATS | 8 |  | Previous Year Current Billing Period To Date (PY CB To) |
| 15 | `PY_CUR_AVG_COMP` | DEC | 16 |  | Previous Year Current BP Average Consumption (PY CB  Comp) |
| 16 | `PY_PREV_AB` | DATS | 8 |  | Previous Year Previous Billing Period From Date (PB-1 From) |
| 17 | `PY_PREV_BIS` | DATS | 8 |  | Previous Year Previous Billing Period To Date (PB-1 To) |
| 18 | `PY_PREV_AVG_COMP` | DEC | 16 |  | Previous Year Previous BP Average Consumption (PB-1 Comp) |
| 19 | `FIRST_PERC` | CURR | 13 |  | Percentage Increase of First Period |
| 20 | `SEC_PERC` | CURR | 13 |  | Percentage Increase of Second Period |
| 21 | `X_PERC` | CURR | 13 |  | High Consumption - X Percentage |
| 22 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 23 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 24 | `CREATION_TIME` | TIMS | 6 |  | System Time |
| 25 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 26 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
