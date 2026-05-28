# ZISED_LPDEL_DTL
**Description:** Load Profile Service Delivery Missing intervals
**Total Fields:** 7
**Key Fields:** MANDT, SEQNUM, REPORTDATE, STARTDATE, STARTTIME

## Programs Using This Table
- `zised0047`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQNUM` | NUMC | 15 | 🔑 | Sequence number |
| 3 | `REPORTDATE` | DATS | 8 | 🔑 | Date |
| 4 | `STARTDATE` | DATS | 8 | 🔑 | Date |
| 5 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 6 | `ENDDATE` | DATS | 8 |  | Date |
| 7 | `ENDTIME` | TIMS | 6 |  | Time |
