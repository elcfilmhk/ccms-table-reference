# ZISFIFINALAC
**Description:** Final Account table
**Total Fields:** 8
**Key Fields:** MANDT, RPTDATE, VKONT

## Programs Using This Table
- `zisfi0038`
- `zisfi0220`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPTDATE` | DATS | 8 | 🔑 | Report Date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `TARIFF` | CHAR | 10 |  | Rate category |
| 5 | `MODATE` | DATS | 8 |  | Move-Out Date |
| 6 | `FNBILL_DATE` | DATS | 8 |  | Final Bill date |
| 7 | `WODATE` | DATS | 8 |  | Write off date |
| 8 | `ABGRD` | CHAR | 2 |  | Posting Reason (For Write-Offs And Transfer Postings) |
