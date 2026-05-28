# ZISCSTARFILESUM
**Description:** CEP: Output data summary
**Total Fields:** 6
**Key Fields:** MANDT, SOURCEFROM, SOURCENAME, GENDATE, GENTIME

## Programs Using This Table
- `ziscs0444`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCEFROM` | CHAR | 10 | 🔑 | Data Source Identifier |
| 3 | `SOURCENAME` | CHAR | 100 | 🔑 | File name or Table name |
| 4 | `GENDATE` | DATS | 8 | 🔑 | File generation date |
| 5 | `GENTIME` | TIMS | 6 | 🔑 | File generation time |
| 6 | `TOTALNUMREC` | INT4 | 10 |  | Total number of records |
