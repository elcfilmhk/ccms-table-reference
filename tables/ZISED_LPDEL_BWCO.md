# ZISED_LPDEL_BWCO
**Description:** Transfer to BW Control table
**Total Fields:** 5
**Key Fields:** MANDT, REPORTDATE, SERVICETYPE, AEDAT

## Programs Using This Table
- `zised0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORTDATE` | DATS | 8 | 🔑 | Reported Date |
| 3 | `SERVICETYPE` | CHAR | 2 | 🔑 | Load Profile Service Type |
| 4 | `AEDAT` | DATS | 8 | 🔑 | Date of Last Change |
| 5 | `AEZET` | TIMS | 6 |  | Time last change was made |
