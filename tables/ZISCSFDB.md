# ZISCSFDB
**Description:** Fixed Date Billing Creation Statistics Table
**Total Fields:** 9
**Key Fields:** MANDT, CREDAT

## Programs Using This Table
- `ziscs0160`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CREDAT` | DATS | 8 | 🔑 | Creation date |
| 3 | `CRENUM` | NUMC | 10 |  | Counter |
| 4 | `OUTNUM` | NUMC | 10 |  | Counter |
| 5 | `DELNUM` | NUMC | 10 |  | Counter |
| 6 | `YTDNUM` | NUMC | 10 |  | Counter |
| 7 | `EBLNUM` | NUMC | 10 |  | Counter |
| 8 | `SMSNUM` | NUMC | 10 |  | Counter |
| 9 | `FAXNUM` | NUMC | 10 |  | Counter |
