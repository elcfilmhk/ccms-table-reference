# ZISEDILPMISSRPT
**Description:** Interval Load Profile missing Report
**Total Fields:** 7
**Key Fields:** MANDT, SERNR, PROFILE, STARTDATE, STARTTIME

## Programs Using This Table
- `zised0062`
- `zised0063`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 4 | `STARTDATE` | DATS | 8 | 🔑 | Date |
| 5 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 6 | `ENDDATE` | DATS | 8 |  | Date |
| 7 | `ENDTIME` | TIMS | 6 |  | Time |
