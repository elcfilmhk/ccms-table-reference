# ZISBISUPPLTR
**Description:** Suppression Correspondence table
**Total Fields:** 6
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbi0124`
- `ziscs0265`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 4 | `OPBEL` | CHAR | 12 |  | Number of print document |
| 5 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 6 | `TOTAL_AMNT` | CURR | 13 |  | Total Amount |
