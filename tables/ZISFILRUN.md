# ZISFILRUN
**Description:** Report Last Run Date for Security Deposit Review
**Total Fields:** 6
**Key Fields:** MANDT, ZZREPORT, ZZTRIGGER

## Programs Using This Table
- `zisfi0025`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZREPORT` | CHAR | 25 | 🔑 | Report Name |
| 3 | `ZZTRIGGER` | CHAR | 1 | 🔑 | Triggering Event |
| 4 | `ZZDATE` | DATS | 8 |  | Last Run Date |
| 5 | `ZZTIME` | TIMS | 6 |  | Last Run Time |
| 6 | `ZZUSERID` | CHAR | 12 |  | Last Run by User ID |
