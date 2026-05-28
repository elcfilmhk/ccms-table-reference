# ZISCSJOBID
**Description:** Custom table for ICS01  - Process ID
**Total Fields:** 12
**Key Fields:** MANDT, REPID, PID

## Programs Using This Table
- `ziscs0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `PID` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `TOTPID` | NUMC | 5 |  | 5 Character Numeric NUMC |
| 5 | `LHAUS` | CHAR | 30 |  | Connection Object |
| 6 | `HHAUS` | CHAR | 30 |  | Connection Object |
| 7 | `TIMESTAND` | TIMS | 6 |  | System Time |
| 8 | `SEQ_NUM` | CHAR | 8 |  | Character field, 8 characters long |
| 9 | `ACCT_COUNT` | CHAR | 9 |  | Character field of 9 digits |
| 10 | `INST_COUNT` | CHAR | 9 |  | Character field of 9 digits |
| 11 | `OUTGOING` | CHAR | 225 |  | Container for character data with the length 225 |
| 12 | `FILENAME` | CHAR | 225 |  | Container for character data with the length 225 |
