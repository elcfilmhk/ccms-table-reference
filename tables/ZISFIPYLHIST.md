# ZISFIPYLHIST
**Description:** Power Your Love Payment History
**Total Fields:** 24
**Key Fields:** MANDT, PROCUSER, PROCDATETIME, ITEM_NO

## Programs Using This Table
- `zisfi0253`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROCUSER` | CHAR | 12 | 🔑 | User/Program who created the record |
| 3 | `PROCDATETIME` | NUMC | 14 | 🔑 | Datetime when EAI file is processed (YYYYMMDDhhmmss) |
| 4 | `ITEM_NO` | INT2 | 5 | 🔑 | PYL EAI Interface file line item number |
| 5 | `POSTDATE` | DATS | 8 |  | Posting Date |
| 6 | `SRC_INTF_ID` | CHAR | 20 |  | Source Interface ID |
| 7 | `BILL_TYPE` | CHAR | 2 |  | Bill Type field from EAI file |
| 8 | `SUBCHARGE` | CHAR | 2 |  | Sub-Charge field from EAI file |
| 9 | `PNOTE` | CHAR | 12 |  | Payment Note number |
| 10 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 11 | `PAYMENT_AMT` | DEC | 13 |  | Payment Amount |
| 12 | `PAYMENT_MEANS` | CHAR | 3 |  | Payment Means |
| 13 | `STORE_NO` | CHAR | 6 |  | Store Number field from EAI file |
| 14 | `TERMINAL_NO` | CHAR | 6 |  | Terminal Number field from EAI file |
| 15 | `ADD_INFO` | CHAR | 80 |  | Additional Info field from EAI file |
| 16 | `VALUEDATE` | DATS | 8 |  | Value Date |
| 17 | `CHQ_NO` | CHAR | 13 |  | Cheque Number field from EAI file |
| 18 | `PROC_RS` | CHAR | 1 |  | PYL Payment Processing Result |
| 19 | `PROC_RS_REASON` | CHAR | 10 |  | Reason code for PYL payment process result |
| 20 | `SAKNR` | CHAR | 10 |  | G/L Account Number |
| 21 | `REF_PROCUSER` | CHAR | 12 |  | User Name part of Referenced record key |
| 22 | `REF_PROCDATETIME` | NUMC | 14 |  | Date time part of Referenced record key (YYYYMMDDhhmmss) |
| 23 | `REF_ITEM_NO` | INT2 | 5 |  | Item Number part of Referenced record key |
| 24 | `REMARKS` | CHAR | 600 |  | Char 600 |
