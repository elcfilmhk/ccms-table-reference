# ZISBISUPPHIST
**Description:** Bill Printing suppression history table
**Total Fields:** 34
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0122`
- `zisbi0153`
- `zisbi0158`
- `zisbi0160`
- `zisbi0167`
- `zisbi0167_ami`
- `zisbi0167_bw`
- `zisbi0205`
- `ziscs0252`
- `ziscs0263`
- `ziscs0517`
- `ziscs0718`
- `ziscs0720`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 6 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 7 | `ZZBILLID` | CHAR | 2 |  | Bill ID |
| 8 | `ZZDELIVERY` | CHAR | 1 |  | Delivery Method |
| 9 | `DISPATCH_CONTROL` | CHAR | 4 |  | Dispatch Control |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `PAY_METHOD` | CHAR | 1 |  | Payment method |
| 12 | `REGULAR_BILL` | CHAR | 1 |  | Regular bill indicator |
| 13 | `BF_AMNT` | CURR | 13 |  | Brought forward amount |
| 14 | `CURR_CHARGE` | CURR | 13 |  | Current amount |
| 15 | `TOTAL_AMNT` | CURR | 13 |  | Total Amount |
| 16 | `GOVT_BAL` | CURR | 13 |  | Government remaining balance |
| 17 | `OPT_OUT` | CHAR | 1 |  | Opt-out indicator (BP) |
| 18 | `OPT_OUT_CA` | CHAR | 1 |  | Opt-out indicator (CA) |
| 19 | `REVERSE_IND` | CHAR | 1 |  | Partial /full reversal indicator |
| 20 | `BY_OPTOUT` | CHAR | 1 |  | Receive due to opt out |
| 21 | `SMALL_IND` | CHAR | 1 |  | Small amount indicator |
| 22 | `PHYSICAL_SUPP` | CHAR | 1 |  | Suppression indicator |
| 23 | `ZZPAY_OPT` | CHAR | 2 |  | FiT Payment Option |
| 24 | `ZZPAY_OPT_EEUS` | CHAR | 2 |  | Payment Method |
| 25 | `ZZPAY_OPT_DR` | CHAR | 2 |  | DR Customer payment option |
| 26 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 27 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 28 | `CREATION_TIME` | TIMS | 6 |  | Time of Print Document Creation |
| 29 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 30 | `PRINT_TIME` | TIMS | 6 |  | Printed time |
| 31 | `AENAM` | CHAR | 12 |  | Printed by |
| 32 | `MODIFIED_DAT` | DATS | 8 |  | Modify date |
| 33 | `MODIFIED_TIME` | TIMS | 6 |  | Modified Time |
| 34 | `MODIFIED_BY` | CHAR | 12 |  | Modified by |
