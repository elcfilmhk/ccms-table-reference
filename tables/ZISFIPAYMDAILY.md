# ZISFIPAYMDAILY
**Description:** Daily Payment Statistics Table
**Total Fields:** 34
**Key Fields:** MANDT, BTHPERIOD, BTHDAY, PYMTCHNL, POSTDATE, VALUEDATE

## Programs Using This Table
- `zisfi0003`
- `zisfi0011`
- `zisfi0012`
- `zisfi0013`
- `zisfi0015`
- `zisfi0023`
- `zisfi0127`
- `zisfi0128`
- `zisfi0129`
- `zisfi0133`
- `zisfi0160`
- `zisfi0163`
- `zisfi0171`
- `zisfi0171_new`
- `zisfi0196`
- `zisfi0209`
- `zisfi0222`
- `zisfi0233`
- `zisfi0252`
- `zisfi0253`
- `zisfi0280`
- `zisfi0312`
- `zisfi0323`
- `zisfi0331`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BTHPERIOD` | CHAR | 6 | 🔑 | Period (MMYYYY) |
| 3 | `BTHDAY` | CHAR | 2 | 🔑 | Day (DD) |
| 4 | `PYMTCHNL` | CHAR | 2 | 🔑 | Payment Channel |
| 5 | `POSTDATE` | DATS | 8 | 🔑 | Posting Date |
| 6 | `VALUEDATE` | DATS | 8 | 🔑 | Value Date |
| 7 | `PYMT_COUNT` | NUMC | 6 |  | Payment Count |
| 8 | `PYMT_AMT` | CURR | 12 |  | Payment Amount |
| 9 | `ATM_CNT` | NUMC | 6 |  | Payment Count (ATM) |
| 10 | `ATM_AMT` | CURR | 12 |  | Payment Amount (ATM) |
| 11 | `INET_CNT` | NUMC | 6 |  | Payment Count (Internet) |
| 12 | `INET_AMT` | CURR | 12 |  | Payment Amount (Internet) |
| 13 | `PHONE_CNT` | NUMC | 6 |  | Payment Count (Phone banking) |
| 14 | `PHONE_AMT` | CURR | 12 |  | Payment Amount (Phone banking) |
| 15 | `STUB_CNT` | NUMC | 6 |  | Stub Count |
| 16 | `STUB_AMT` | CURR | 12 |  | Stub Amount |
| 17 | `CASH_CNT` | NUMC | 6 |  | Cash Count |
| 18 | `CASH_AMT` | CURR | 12 |  | Cash Amount |
| 19 | `CHEQUE_CNT` | NUMC | 6 |  | Cheque Count |
| 20 | `CHEQUE_AMT` | CURR | 12 |  | Cheque Amount |
| 21 | `REMIT_CNT` | NUMC | 6 |  | Bank Remittance Count |
| 22 | `REMIT_AMT` | CURR | 12 |  | Bank Remittance Amount |
| 23 | `S_F_STUB_CNT` | NUMC | 6 |  | Single Full Stub Count |
| 24 | `S_F_CHEQUE_CNT` | NUMC | 6 |  | Single Full Cheque Count |
| 25 | `NS_F_STUB_CNT` | NUMC | 6 |  | Non-single Full Stub Count |
| 26 | `NS_F_CHEQUE_CNT` | NUMC | 6 |  | Non-single Full Cheque Count |
| 27 | `CHQ_STUB_CNT` | NUMC | 6 |  | Cheque Only Stub Count |
| 28 | `CHQ_CHEQUE_CNT` | NUMC | 6 |  | Cheque Only Cheque Count |
| 29 | `STUB_TTL_CNT` | NUMC | 6 |  | Stub Total Count |
| 30 | `CHQ_TTL_CNT` | NUMC | 6 |  | Cheque Total Count |
| 31 | `CHQ_TTL_AMT` | CURR | 12 |  | Cheque Total Amount |
| 32 | `RTN_LOT_ID` | CHAR | 12 |  | Returns Lot |
| 33 | `RTN_CNT` | NUMC | 6 |  | Return Count |
| 34 | `RTN_AMT` | CURR | 12 |  | Return Amount |
