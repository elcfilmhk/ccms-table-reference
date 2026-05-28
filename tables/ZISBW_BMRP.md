# ZISBW_BMRP
**Description:** BW Data extraction
**Total Fields:** 11
**Key Fields:** MANDT, REPID, FRDAT, TODAT, IDENT1, IDENT2, IDENT3

## Programs Using This Table
- `zisbi0001`
- `zisbi0014`
- `zisbi0014t`
- `zisbi0063`
- `zisfi0025`
- `zisfi0205`
- `zisfi0340`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `FRDAT` | DATS | 8 | 🔑 | From Date |
| 4 | `TODAT` | DATS | 8 | 🔑 | To Date |
| 5 | `IDENT1` | CHAR | 20 | 🔑 | Level 1 Identification |
| 6 | `IDENT2` | CHAR | 20 | 🔑 | Level 2 Identification |
| 7 | `IDENT3` | CHAR | 20 | 🔑 | Level 3 Identification |
| 8 | `BWCNT` | INT4 | 10 |  | Count for BW extraction |
| 9 | `BWAMT` | DEC | 15 |  | Amount for BW extraction |
| 10 | `CPUDT` | DATS | 8 |  | Date of entry |
| 11 | `CPUTM` | TIMS | 6 |  | Time of Entry |
