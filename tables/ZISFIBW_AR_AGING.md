# ZISFIBW_AR_AGING
**Description:** Output table for BW Integration Report
**Total Fields:** 16
**Key Fields:** MANDT, LINE, TARIFTYP, TARIFTYP_TXT, ERDAT, ERZET, ERNAM

## Programs Using This Table
- `zisfi0116`
- `zisfi0116_test`
- `zisfi0116_test2`
- `zisfi0116_test3`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LINE` | NUMC | 2 | 🔑 | Line |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 4 | `TARIFTYP_TXT` | CHAR | 15 | 🔑 | Rate category |
| 5 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 6 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 7 | `ERNAM` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
| 8 | `NOT_DUE` | CURR | 13 |  | Not Due |
| 9 | `LIVE1` | CURR | 13 |  | 1 - 30 Days |
| 10 | `LIVE31` | CURR | 13 |  | 31 - 60 Days |
| 11 | `LIVE61` | CURR | 13 |  | 61 - 90 Days |
| 12 | `LIVE90` | CURR | 13 |  | > 90 Days Live Acct |
| 13 | `NONLIVE` | CURR | 13 |  | > 90 Days Non-Live Acct |
| 14 | `OVERALL` | CURR | 13 |  | Overall |
| 15 | `WAERS` | CUKY | 5 |  | Transaction Currency |
| 16 | `RUNDT` | DATS | 8 |  | Batch Run Date |
