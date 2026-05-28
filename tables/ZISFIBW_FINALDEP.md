# ZISFIBW_FINALDEP
**Description:** Final Bill Balance and Deposit Held
**Total Fields:** 13
**Key Fields:** MANDT, RUNDT, VKONT, OPBEL

## Programs Using This Table
- `zisfi0315`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDT` | DATS | 8 | 🔑 | Batch run date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 5 | `FINAL_CHARGE` | CURR | 13 |  | Final charge before offset with deposit |
| 6 | `DEP_RETURNED` | CURR | 13 |  | Deposit Returned in Final bill |
| 7 | `BILL_BALANCE` | CURR | 13 |  | Final Bill Balance |
| 8 | `DEP_REQ` | CURR | 17 |  | Required deposit |
| 9 | `CASH_DEP` | CURR | 17 |  | Total cash deposit held |
| 10 | `BK_GUARANTEE` | CURR | 17 |  | Total bank guarantee held |
| 11 | `TWAERS` | CUKY | 5 |  | Transaction Currency |
| 12 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 13 | `ERZET` | TIMS | 6 |  | Entry time |
