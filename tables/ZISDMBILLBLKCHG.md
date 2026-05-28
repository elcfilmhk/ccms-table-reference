# ZISDMBILLBLKCHG
**Description:** Billing Block Change Case
**Total Fields:** 9
**Key Fields:** MANDT, CASE_NR

## Programs Using This Table
- `zisdm0050`
- `zisdm0392`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CASE_NR` | CHAR | 10 | 🔑 | Change Number of Document |
| 3 | `RUN_DATE` | DATS | 8 |  | Date |
| 4 | `VERTRAG` | CHAR | 10 |  | Contract |
| 5 | `UPD_DATE` | DATS | 8 |  | Date |
| 6 | `UPD_TIME` | TIMS | 6 |  | Time |
| 7 | `OUTSORT_CASE` | CHAR | 10 |  | Outsort Case |
| 8 | `OLD_ABRSPERR` | CHAR | 2 |  | Reason for blocking billing |
| 9 | `NEW_ABRSPERR` | CHAR | 2 |  | Reason for blocking billing |
