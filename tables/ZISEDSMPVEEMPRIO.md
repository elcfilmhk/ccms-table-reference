# ZISEDSMPVEEMPRIO
**Description:** SMP VEE: Profile Status Priority
**Total Fields:** 7
**Key Fields:** MANDT, ERRORCODE, KEYNAME

## Programs Using This Table
- `zrvee_pst_imp_vd_chld`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERRORCODE` | NUMC | 3 | 🔑 | Error code of consistency check |
| 3 | `KEYNAME` | CHAR | 30 | 🔑 | VEE Variable Name |
| 4 | `ERRORTEXT` | CHAR | 50 |  | Description of error code for consistency check |
| 5 | `CONCHECK` | CHAR | 10 |  | Consistency check for profile import |
| 6 | `SEQNO` | CHAR | 3 |  | Sequence Number |
| 7 | `STATUS` | NUMC | 2 |  | Status |
