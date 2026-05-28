# ZISDMARVCFG
**Description:** Archiving Job Configuration
**Total Fields:** 14
**Key Fields:** MANDT, ARCOBJECT, PROCESSNAME, VARIANTNAME, EVENTTRIGGER, FREQUENCY, ARCMONTH, WEEKNUMBER, DAYOFWEEK

## Programs Using This Table
- `zisdm0352`
- `zisdm0353`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ARCOBJECT` | CHAR | 10 | 🔑 | Archiving Object |
| 3 | `PROCESSNAME` | CHAR | 10 | 🔑 | Archiving Process Name |
| 4 | `VARIANTNAME` | CHAR | 20 | 🔑 | Archiving Variant Name |
| 5 | `EVENTTRIGGER` | CHAR | 32 | 🔑 | Background Processing Event |
| 6 | `FREQUENCY` | CHAR | 2 | 🔑 | Archiving Frequency |
| 7 | `ARCMONTH` | CHAR | 3 | 🔑 | Archiving Month |
| 8 | `WEEKNUMBER` | NUMC | 1 | 🔑 | Archiving Week Number |
| 9 | `DAYOFWEEK` | CHAR | 3 | 🔑 | Day of week |
| 10 | `EFLAG` | CHAR | 1 |  | Archiving EFlag |
| 11 | `BATCHNAME` | CHAR | 10 |  | Archiving Batch Name |
| 12 | `SEQNUMBER` | NUMC | 4 |  | Sequence Num. |
| 13 | `DESCRIPTION` | CHAR | 80 |  | Archiving description |
| 14 | `DELFLAG` | CHAR | 1 |  | Job deletion flag |
