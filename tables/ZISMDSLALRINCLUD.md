# ZISMDSLALRINCLUD
**Description:** Storing the installation list for Load research
**Total Fields:** 6
**Key Fields:** MANDT, ANLAGE, EFFSTARTDATE

## Programs Using This Table
- `zised0049`
- `zised0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `EFFSTARTDATE` | DATS | 8 | 🔑 | Effective start date |
| 4 | `EFFENDDATE` | DATS | 8 |  | Effective End Date |
| 5 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 6 | `UNAME` | CHAR | 12 |  | User Name |
