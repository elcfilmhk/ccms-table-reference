# ZISCSDOMEO_BAL
**Description:** Table for Domeo IDs with updated Balance from Magento
**Total Fields:** 10
**Key Fields:** MANDT, CONTRACT_ACCOUNT

## Programs Using This Table
- `zisbi0240`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DOMEO_ID` | CHAR | 100 |  | Contact |
| 4 | `BALANCE` | CHAR | 10 |  | Domeo Points balance |
| 5 | `EXECUTION_DATE` | DATS | 8 |  | Batch Run date |
| 6 | `CREATION_DATE` | DATS | 8 |  | Date on which the object was created |
| 7 | `CREATION_TIME` | TIMS | 6 |  | Time at which the object was created |
| 8 | `STATUS` | CHAR | 1 |  | Status |
| 9 | `RETURN_CODE` | CHAR | 2 |  | return code |
| 10 | `MESSAGE` | CHAR | 100 |  | Message returned from Magento |
