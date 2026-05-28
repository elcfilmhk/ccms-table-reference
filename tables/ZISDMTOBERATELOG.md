# ZISDMTOBERATELOG
**Description:** Log for mass change to be reprogram rate ID
**Total Fields:** 8
**Key Fields:** MANDT, SEQNO

## Programs Using This Table
- `zisdm0016`
- `zisdm0316`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQNO` | NUMC | 10 | 🔑 | Sequence number |
| 3 | `SERNR` | CHAR | 18 |  | Serial Number |
| 4 | `REPRGRATEID` | CHAR | 8 |  | The ID of the re-program rate |
| 5 | `BEFREPRGRATEID` | CHAR | 8 |  | The ID of the re-program rate |
| 6 | `AFTREPRGRATEID` | CHAR | 8 |  | The ID of the re-program rate |
| 7 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 8 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
