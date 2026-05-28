# ZISDMINVALIDMRID
**Description:** Meter reading document with invalid meter reader ID
**Total Fields:** 7
**Key Fields:** MANDT, RUNDATE, GERNR, ADATSOLL, ABLESGR

## Programs Using This Table
- `zisdm0050`
- `zisdm0259`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Batch Run Date |
| 3 | `GERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 5 | `ABLESGR` | CHAR | 2 | 🔑 | Meter reading reason |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `EMPLOYEEID` | CHAR | 8 |  | User ID |
