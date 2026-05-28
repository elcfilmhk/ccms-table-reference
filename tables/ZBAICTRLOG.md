# ZBAICTRLOG
**Description:** Interface control - transaction logging table
**Total Fields:** 15
**Key Fields:** MANDT, SYSID, REPID, FUNCT, RN_COUNTER, MSGSEQ

## Programs Using This Table
- `zbaicri06`
- `zisfi0171`
- `zisfi0171_new`
- `zisfi0253`
- `zisfi0331`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SYSID` | CHAR | 8 | 🔑 | Name of SAP System |
| 3 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 4 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 5 | `RN_COUNTER` | NUMC | 8 | 🔑 | Interface control - sequential number |
| 6 | `MSGSEQ` | NUMC | 8 | 🔑 | Interface control - sequential number |
| 7 | `MSG_ID` | CHAR | 20 |  | Application Area |
| 8 | `MSGNR` | CHAR | 3 |  | Message number |
| 9 | `MSGTYP` | CHAR | 1 |  | Batch input message type |
| 10 | `MSGV1` | CHAR | 100 |  | Variable part of a message |
| 11 | `MSGV2` | CHAR | 100 |  | Variable part of a message |
| 12 | `MSGV3` | CHAR | 100 |  | Variable part of a message |
| 13 | `MSGV4` | CHAR | 100 |  | Variable part of a message |
| 14 | `MSGDATE` | DATS | 8 |  | Interface control - date |
| 15 | `MSGTIME` | TIMS | 6 |  | Interface control - time |
