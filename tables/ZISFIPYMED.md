# ZISFIPYMED
**Description:** Temp.  table to handle records of Cheque, DD, and  EFT Enh
**Total Fields:** 13
**Key Fields:** MANDT, TYPE, BATCHRUNDATE, RUNID, RUNDATE, JOBNUMBER, COUNTER

## Programs Using This Table
- `zisfi0066`
- `zisfi0140`
- `ztest_zisfi0066`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 1 | 🔑 | Indicators |
| 3 | `BATCHRUNDATE` | DATS | 8 | 🔑 | Date |
| 4 | `RUNID` | CHAR | 6 | 🔑 | Additional Identification Characteristic |
| 5 | `RUNDATE` | DATS | 8 | 🔑 | Date ID |
| 6 | `JOBNUMBER` | NUMC | 10 | 🔑 | Unique Job Number in a Task |
| 7 | `COUNTER` | NUMC | 6 | 🔑 | Line number |
| 8 | `TEXT1` | CHAR | 250 |  | PAW - Message text |
| 9 | `TEXT2` | CHAR | 250 |  | PAW - Message text |
| 10 | `TEXT3` | CHAR | 250 |  | PAW - Message text |
| 11 | `TEXT4` | CHAR | 250 |  | PAW - Message text |
| 12 | `UPDATEFLAG` | CHAR | 1 |  | Text Update Flag |
| 13 | `DOCUMENTNUM` | CHAR | 24 |  | Reference to Payment Document |
