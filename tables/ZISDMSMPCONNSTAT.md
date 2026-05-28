# ZISDMSMPCONNSTAT
**Description:** SMP Meter connectivity status
**Total Fields:** 7
**Key Fields:** MANDT, METER, ENDPOINTID

## Programs Using This Table
- `zisdm0349`
- `zisdm0402`
- `zisdm0412`
- `zisdm0413`
- `zrdm_m_repl_rep`
- `zrdm_mr_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METER` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `ENDPOINTID` | CHAR | 72 | 🔑 | The End point ID of the SMP meter |
| 4 | `COLLECTOR` | CHAR | 72 |  | The collector id the SMP meter connected to |
| 5 | `STATUS` | CHAR | 10 |  | The status of the connection |
| 6 | `LASTREADDATE` | DATS | 8 |  | The last read date of the SMP meter |
| 7 | `LASTREADTIME` | TIMS | 6 |  | The last read time of the SMP meter |
