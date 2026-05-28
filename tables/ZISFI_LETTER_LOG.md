# ZISFI_LETTER_LOG
**Description:** Table for Corporate Letter/Electricity Bill Form Log
**Total Fields:** 20
**Key Fields:** MANDT, TEMPLATE_ID, LETTER_TYP, CREATE_DATE, CREATE_TIME, COUNTER

## Programs Using This Table
- `zisbi0224`
- `zisfi0038`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TEMPLATE_ID` | CHAR | 30 | 🔑 | Template ID |
| 3 | `LETTER_TYP` | CHAR | 20 | 🔑 | Letter Form Type |
| 4 | `CREATE_DATE` | DATS | 8 | 🔑 | Created On |
| 5 | `CREATE_TIME` | TIMS | 6 | 🔑 | Time created |
| 6 | `COUNTER` | NUMC | 5 | 🔑 | Counter Bulk Letter Log Table |
| 7 | `CREATE_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `CONTRACT_ACCOUNT` | CHAR | 12 |  | Contract Account Number |
| 9 | `OT_CONTRACT_ACCOUNT` | CHAR | 12 |  | Contract Account Number |
| 10 | `BUSINESS_PARTNER` | CHAR | 10 |  | Business Partner Number |
| 11 | `CURRENT_BALANCE` | CURR | 13 |  | Current Balance |
| 12 | `DEPOSIT_HELD` | CURR | 13 |  | Deposit Held |
| 13 | `DUNNING_LEVEL` | NUMC | 2 |  | Dunning Level |
| 14 | `DUNNING_LOCK` | CHAR | 1 |  | Dunning Lock |
| 15 | `PAYMENT_METHOD` | CHAR | 4 |  | Payment Method |
| 16 | `MOVE_OUT_DATE` | DATS | 8 |  | Actual move-out date |
| 17 | `POSTAL_ADDRESS` | CHAR | 100 |  | Postal Address |
| 18 | `PRINT_FLAG` | CHAR | 1 |  | Print Flag |
| 19 | `UPDATING_ACT` | CHAR | 10 |  | Updating Activity |
| 20 | `CRM_ACT_CRTD` | CHAR | 1 |  | CRM Activity Created |
