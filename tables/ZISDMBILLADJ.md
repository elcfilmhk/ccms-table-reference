# ZISDMBILLADJ
**Description:** Customer table for Billing Adjustment Automation
**Total Fields:** 10
**Key Fields:** MANDT, CONTACCT, CONTRACT

## Programs Using This Table
- `zisdm0150`
- `zisdm0170`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CONTRACT` | CHAR | 10 | 🔑 | Contract |
| 4 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 5 | `SCHMRDATE_BEG` | DATS | 8 |  | Date |
| 6 | `SCHMRDATE_END` | DATS | 8 |  | Date |
| 7 | `UNAME` | CHAR | 12 |  | User Name |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `DATE_CONF` | DATS | 8 |  | Confirmation Date |
| 10 | `BCREASON` | CHAR | 2 |  | Reason for Reversal |
