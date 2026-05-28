# ZERCHO_REMARKS
**Description:** Remarks for Billing Outsort
**Total Fields:** 6
**Key Fields:** MANDT, BELNR

## Programs Using This Table
- `zbi_unbill`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `REMARKS` | CHAR | 100 |  | Remarks |
| 4 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 5 | `AETIM` | TIMS | 6 |  | Time |
| 6 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
