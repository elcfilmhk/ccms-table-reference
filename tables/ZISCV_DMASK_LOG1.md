# ZISCV_DMASK_LOG1
**Description:** Output Log for data masking threads
**Total Fields:** 14
**Key Fields:** MANDT, RUN_DT, RUN_USER, LOG_DT, THREAD_NAME, SEQ

## Programs Using This Table
- `ziscv_datamask1`
- `ziscv_datamask1_thread`
- `zziscv_datamask1`
- `zziscv_datamask1_thread`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUN_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `RUN_USER` | CHAR | 12 | 🔑 | User Name |
| 4 | `LOG_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `THREAD_NAME` | CHAR | 30 | 🔑 | Rules with Same thread name processed in same thread |
| 6 | `SEQ` | INT4 | 10 | 🔑 | Natural number |
| 7 | `O_RESULT` | CHAR | 1 |  | Result: S:Success, F:Failure |
| 8 | `TYPE` | CHAR | 1 |  | Message type: S Success, E Error, W Warning, I Info, A Abort |
| 9 | `RETURN_CODE` | CHAR | 100 |  | Return Code |
| 10 | `MESSAGE` | CHAR | 220 |  | Message Text |
| 11 | `KEY1` | CHAR | 40 |  | Character field of length 40 |
| 12 | `KEY2` | CHAR | 40 |  | Character field of length 40 |
| 13 | `KEY3` | CHAR | 40 |  | Character field of length 40 |
| 14 | `KEY4` | CHAR | 40 |  | Character field of length 40 |
