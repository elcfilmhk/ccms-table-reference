# ZISCSOTPDETAILS
**Description:** Custom table to save details related to OTP
**Total Fields:** 8
**Key Fields:** MANDT, CONTRACT_ACCOUNT, CONTACT

## Programs Using This Table
- `zcxt_datamigration_01`
- `ziscs0602`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CONTACT` | CHAR | 100 | 🔑 | Contact |
| 4 | `CHANNEL` | CHAR | 1 |  | Channel |
| 5 | `FAILED_COUNTER` | INT1 | 3 |  | FAILED COUNTER |
| 6 | `LAST_TIME_STAMP` | CHAR | 14 |  | Last login timestamp |
| 7 | `CREATION_DATE` | DATS | 8 |  | Field of type DATS |
| 8 | `STATUS` | CHAR | 1 |  | Status |
