# ZISBIREB
**Description:** Rebate 1
**Total Fields:** 19
**Key Fields:** MANDT, RB_YEAR, VKONT, VERTRAG

## Programs Using This Table
- `zisbi0025`
- `zisbi0025_1`
- `zisfi0078`
- `zisfi0258`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RB_YEAR` | NUMC | 4 | 🔑 | Year for period |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 5 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 6 | `GEMFAKT` | CHAR | 1 |  | Invoice Contracts Jointly (Mandatory Contracts) |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `LAST_BL` | DATS | 8 |  | Last Billing Date |
| 9 | `WERT1` | DEC | 16 |  | Entry value (installed value) for a device |
| 10 | `NR_DOC` | INT4 | 10 |  | Number of documents |
| 11 | `RB_AMT` | DEC | 16 |  | Rebate amount |
| 12 | `POST_DATE` | DATS | 8 |  | Posting date |
| 13 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 14 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 15 | `ERTIM` | TIMS | 6 |  | Time Created |
| 16 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 17 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 18 | `AETIM` | TIMS | 6 |  | Time of Last Change |
| 19 | `BILL_ORD` | CHAR | 1 |  | Missing Billing Order ('X' = true, space = false) |
