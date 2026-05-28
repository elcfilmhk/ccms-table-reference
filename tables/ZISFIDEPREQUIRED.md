# ZISFIDEPREQUIRED
**Description:** Contract account overview
**Total Fields:** 15
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbw0013`
- `zisfi0113`
- `zisfi0113_upd`
- `zisfi0123`
- `zisfi0124`
- `zisfi0131`
- `zisfi0137`
- `zisfi0200`
- `zisfi0236`
- `zisfi0315`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 4 | `KTOKL` | CHAR | 4 |  | Account class |
| 5 | `DEP_REQ` | CURR | 17 |  | Required deposit |
| 6 | `CASH_DEP` | CURR | 17 |  | Total cash deposit held |
| 7 | `BK_GUARANTEE` | CURR | 17 |  | Total bank guarantee held |
| 8 | `NR_BILL` | INT1 | 3 |  | Number of bill based |
| 9 | `LAST_BILL_DATE` | DATS | 8 |  | Last billing date |
| 10 | `TOTAL_AMNT` | CURR | 17 |  | Total consumption |
| 11 | `MAX_AMNT` | CURR | 17 |  | Max. energy charge |
| 12 | `FB_BUDAT` | DATS | 8 |  | Final bill posting date |
| 13 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 15 | `RWDAT` | DATS | 8 |  | Last review date |
