# ZISBI_REB_HDR
**Description:** Rebate Header
**Total Fields:** 38
**Key Fields:** MANDT, RB_YEAR, VKONT, VERTRAG, SEQ_NO

## Programs Using This Table
- `zisbi0201`
- `zisbi0201_ind`
- `zisbi0201_mu`
- `zisbi0201_tp`
- `zisbi0202`
- `zisbi0203`
- `zisbi0206`
- `zisbi0208`
- `zisbi0209`
- `zisbi0216`
- `zisbi0220`
- `zisbi0221`
- `zisfi0258`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RB_YEAR` | CHAR | 8 | 🔑 | Rebate year and reference |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 5 | `SEQ_NO` | NUMC | 3 | 🔑 | Seq No. |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `GEMFAKT` | CHAR | 1 |  | Invoice Contracts Jointly (Mandatory Contracts) |
| 8 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 9 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 10 | `TOT_REB_CONSUM` | DEC | 13 |  | Total Rebate Consumption |
| 11 | `REBATE` | CURR | 13 |  | Rebate Amount |
| 12 | `BD_CNT` | INT4 | 10 |  | Number of Bill Doc |
| 13 | `UNIT_RATE` | DEC | 17 |  | Rebate unit price |
| 14 | `RB_STATUS` | CHAR | 1 |  | Status |
| 15 | `RB_TYPE` | CHAR | 1 |  | Rebate type |
| 16 | `TRAN_PROC` | CHAR | 12 |  | Transaction process |
| 17 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 18 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 19 | `FINAL_PD` | CHAR | 12 |  | Final bill PD |
| 20 | `BILL_MTHD` | CHAR | 3 |  | Billing method for last bill |
| 21 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 22 | `PD` | CHAR | 12 |  | Number of print document |
| 23 | `REV_PD` | CHAR | 12 |  | Reversal print document number |
| 24 | `REV_DAT` | DATS | 8 |  | Reversal date |
| 25 | `FICADOC` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 26 | `REV_FICADOC` | CHAR | 12 |  | Reversal FI-CA document no. |
| 27 | `PAY_MTHD` | CHAR | 1 |  | Payment method |
| 28 | `REF` | CHAR | 12 |  | Reference |
| 29 | `TP_AMT` | CURR | 13 |  | Total Amount |
| 30 | `PRINT_DOC_1` | CHAR | 12 |  | Print Doc of first invoice |
| 31 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 32 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 33 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 34 | `AENDT` | DATS | 8 |  | Date of last change |
| 35 | `AEZEIT` | TIMS | 6 |  | Time of Change |
| 36 | `AENAME` | CHAR | 12 |  | Last Changed By |
| 37 | `INFO1` | CHAR | 8 |  | Info 1 |
| 38 | `INFO2` | CHAR | 20 |  | Info 2 |
