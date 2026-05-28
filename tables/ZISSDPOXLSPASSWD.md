# ZISSDPOXLSPASSWD
**Description:** Purchase Order Excel File Password History
**Total Fields:** 5
**Key Fields:** MANDT, CREATE_DATE, CREATE_TIME

## Programs Using This Table
- `zmmprs000`
- `zmmprs001`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CREATE_DATE` | DATS | 8 | 🔑 | Creation date |
| 3 | `CREATE_TIME` | TIMS | 6 | 🔑 | Creation Time |
| 4 | `CREATED_BY` | CHAR | 12 |  | Created By |
| 5 | `PASSWORD` | CHAR | 32 |  | Password (Encrypted) |
