# ZBW_ISU_FI_CA_ACC_BAL
**Description:** Output Structure for extractor Z_BW_EXTRACT_FI_CA_ACC_BAL
**Total Fields:** 18
**Key Fields:** _none_

## Programs Using This Table
- `z_bw_extract_fi_ca_acc_bal====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 3 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `AEDATP` | DATS | 8 |  | Date of Last Change |
| 5 | `KTOKL` | CHAR | 4 |  | Account class |
| 6 | `BAL_OPEN` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 7 | `BAL_DUE` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 8 | `BAL_CREDIT` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 9 | `BAL_DOWNPAY` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 10 | `BAL_CSD_PAY` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 11 | `BAL_WRITEOFF` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 12 | `BAL_INS_PLAN` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 13 | `BAL_DEACT_INST` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 14 | `BAL_COLLECT_ITM` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 15 | `BAL_DOUBT_ITM` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 16 | `BAL_INDV_VAL_ADJ` | DEC | 23 |  | Currency amount in BAPI interfaces |
| 17 | `BAPI_CALL_DATE` | DATS | 8 |  | immediate datestamp at time of BAPI FM call |
| 18 | `BAPI_CALL_TIME` | TIMS | 6 |  | immediate timestamp at time of BAPI FM call |
