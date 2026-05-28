# ZISFIRECONSTAT
**Description:** Payment Reconciliation Result
**Total Fields:** 24
**Key Fields:** MANDT, OFFIC, CHDSK, PAYID

## Programs Using This Table
- `zisfi0311`
- `zisfi0318`
- `zisfi0323`
- `zisfi0324`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OFFIC` | CHAR | 3 | 🔑 | Branch in Cash Journal |
| 3 | `CHDSK` | CHAR | 2 | 🔑 | Cash Desk |
| 4 | `PAYID` | CHAR | 80 | 🔑 | Unique Transaction ID |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `BLDAT` | DATS | 8 |  | Document Date in Document |
| 7 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 8 | `AETIM` | TIMS | 6 |  | Time at Which the Object Was Last Changed |
| 9 | `VALUT` | DATS | 8 |  | Value date |
| 10 | `ZZSTEXC` | CHAR | 1 |  | Payment Item Status |
| 11 | `ZCOUNT` | NUMC | 3 |  | Counter |
| 12 | `BETRZ` | CURR | 13 |  | Payment amount in transaction currency |
| 13 | `WAERS` | CUKY | 5 |  | Currency Key |
| 14 | `ZREFKEY1` | CHAR | 30 |  | Reference key1 |
| 15 | `ZREFKEY2` | CHAR | 30 |  | Reference key2 |
| 16 | `ZSCANCODE` | CHAR | 30 |  | Indicator of QR code and bar code |
| 17 | `ZFILLER` | CHAR | 74 |  | FILLER |
| 18 | `ZPAYPOINT` | CHAR | 30 |  | Point of payment |
| 19 | `ZYOURREF` | CHAR | 40 |  | Counter Party Reference |
| 20 | `ZPAYMEDIA` | CHAR | 30 |  | Means of Payment |
| 21 | `ZBILLTYPE` | NUMC | 2 |  | Bill Type |
| 22 | `ZTXINDCATOR` | NUMC | 2 |  | Transaction indicator |
| 23 | `ZSERVFEEIND` | CHAR | 2 |  | Transaction fee indicator |
| 24 | `ZRECONDATE` | DATS | 8 |  | Recon Date |
