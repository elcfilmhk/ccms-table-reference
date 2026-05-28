# ZISFIOPTINPYT
**Description:** Daily Statistic of Opt-in monthly billing by payment channel
**Total Fields:** 10
**Key Fields:** MANDT, BATCH_RUN_DATE, PYMT_CHNNL, VALUT, BUDAT

## Programs Using This Table
- `zisfi0240`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCH_RUN_DATE` | DATS | 8 | 🔑 | Batch run date |
| 3 | `PYMT_CHNNL` | CHAR | 10 | 🔑 | Payment channel indicator |
| 4 | `VALUT` | DATS | 8 | 🔑 | Value date |
| 5 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 6 | `PYMT_METHOD` | CHAR | 1 |  | Payment Method |
| 7 | `SUBM_DATE` | DATS | 8 |  | File submission date |
| 8 | `PYMT_COUNT` | DEC | 5 |  | Payment Count |
| 9 | `PYMT_AMT` | CURR | 12 |  | Payment Amount |
| 10 | `ACCT_COUNT` | DEC | 5 |  | Contract Account Count |
