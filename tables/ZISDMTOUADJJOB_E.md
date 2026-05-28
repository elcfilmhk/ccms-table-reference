# ZISDMTOUADJJOB_E
**Description:** TOU billing device MR adjustment Error Header
**Total Fields:** 8
**Key Fields:** MANDT, ANLAGE, SERNR, ADATSOLL

## Programs Using This Table
- `zisdm0235`
- `zisdm0235_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `VERTRAG` | CHAR | 10 |  | Contract |
| 7 | `ABRSPERR` | CHAR | 2 |  | Reason for blocking billing |
| 8 | `ERROR` | CHAR | 100 |  | Character 100 |
