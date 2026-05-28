# ZBACBIX01
**Description:** IXOS: CISS Bills
**Total Fields:** 5
**Key Fields:** MANDT, ACCNO, TIMESTAMP

## Programs Using This Table
- `z_bapi_bill_presentment=======ft`
- `zbacbix1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACCNO` | NUMC | 10 | 🔑 | Account Number |
| 3 | `TIMESTAMP` | CHAR | 26 | 🔑 | Timestamp |
| 4 | `ISSUEDATE` | DATS | 8 |  | Issue Date |
| 5 | `READDATE` | DATS | 8 |  | Reading Date |
