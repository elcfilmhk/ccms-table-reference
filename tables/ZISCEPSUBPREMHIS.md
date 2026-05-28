# ZISCEPSUBPREMHIS
**Description:** CEP: Store Masked Sub Premise for Service point
**Total Fields:** 6
**Key Fields:** MANDT, VSTELLE, CREATE_DATE, CREATE_TIME

## Programs Using This Table
- `ziscs0444`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `CREATE_DATE` | DATS | 8 | 🔑 | Date |
| 4 | `CREATE_TIME` | TIMS | 6 | 🔑 | Time |
| 5 | `MASKED_PREMISE` | CHAR | 40 |  | Character field of length 40 |
| 6 | `MASKED_SUBPREM` | CHAR | 100 |  | Character 100 |
