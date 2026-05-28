# ZISDMRTEMS
**Description:** Route Management Table
**Total Fields:** 8
**Key Fields:** MANDT, MRU

## Programs Using This Table
- `zisdh0002`
- `zisdh0004`
- `zisdm0027`
- `zisdm0049`
- `zisdm0051`
- `zisdm0082`
- `zisdm0109`
- `zisdmul01`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MRU` | CHAR | 8 | 🔑 | Meter Reading Unit |
| 3 | `ROUTEMSG` | CHAR | 80 |  | Route Message |
| 4 | `LATESTRTTIME` | CHAR | 4 |  | Latest time taken to complete route |
| 5 | `DWNLDATE` | DATS | 8 |  | Download Date |
| 6 | `DWNLNUM` | CHAR | 10 |  | Number of download by MRU |
| 7 | `UPLDDATE` | DATS | 8 |  | Upload Date |
| 8 | `UPLDNUM` | CHAR | 10 |  | Number of upload by MRU |
