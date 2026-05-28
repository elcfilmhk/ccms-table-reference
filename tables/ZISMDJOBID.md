# ZISMDJOBID
**Description:** PROCESS NUMBER FOR MDMS UNIT
**Total Fields:** 8
**Key Fields:** MANDT, REPID, PID

## Programs Using This Table
- `zismd0002`
- `zismd0006`
- `zismd0008`
- `zismd0009`
- `zismd0012`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `PID` | NUMC | 5 | 🔑 | 5 Character Numeric NUMC |
| 4 | `RUNDATE` | DATS | 8 |  | System Date |
| 5 | `TIMESTAND` | TIMS | 6 |  | System Time |
| 6 | `SEQ_NUM` | CHAR | 8 |  | Character field, 8 characters long |
| 7 | `OUTGOING` | CHAR | 225 |  | Container for character data with the length 225 |
| 8 | `FILENAME` | CHAR | 225 |  | Container for character data with the length 225 |
