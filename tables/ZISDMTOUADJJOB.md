# ZISDMTOUADJJOB
**Description:** TOU billing device MR adjustment
**Total Fields:** 11
**Key Fields:** MANDT, ANLAGE, ADATSOLL, SERNR

## Programs Using This Table
- `zisdm0235`
- `zisdm0235_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `VERTRAG` | CHAR | 10 |  | Contract |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `ABRSPERR` | CHAR | 2 |  | Reason for blocking billing |
| 8 | `BILLTYPE` | CHAR | 1 |  | Bill Type |
| 9 | `PID` | NUMC | 5 |  | Process ID |
| 10 | `PROCESSED` | CHAR | 1 |  | Character Field Length 1 |
| 11 | `ADJUSTED` | CHAR | 1 |  | Character Field Length 1 |
