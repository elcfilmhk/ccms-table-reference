# ZISFIWFPAR
**Description:** Table for mass write-off parameters in document posting
**Total Fields:** 39
**Key Fields:** MANDT, LAUFD, LAUFI, ZZJOBNAME, ZZID

## Programs Using This Table
- `zisfi0073`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LAUFD` | DATS | 8 | 🔑 | Date ID |
| 3 | `LAUFI` | CHAR | 5 | 🔑 | Identification for the payment run |
| 4 | `ZZJOBNAME` | CHAR | 32 | 🔑 | Background job name |
| 5 | `ZZID` | NUMC | 12 | 🔑 | Line item number |
| 6 | `FIKEY` | CHAR | 12 |  | Reconciliation Key for General Ledger |
| 7 | `APPL_AREA` | CHAR | 1 |  | Application area |
| 8 | `DOC_SOURCE_KEY` | CHAR | 2 |  | Document Origin Key |
| 9 | `CURRENCY` | CUKY | 5 |  | Transaction Currency |
| 10 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `DOC_DATE` | DATS | 8 |  | Document Date in Document |
| 12 | `POST_DATE` | DATS | 8 |  | Posting Date in the Document |
| 13 | `ENTRY_DATE` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 14 | `ENTRY_TIME` | TIMS | 6 |  | Time of Entry |
| 15 | `TRANS_DATE` | DATS | 8 |  | Translation date |
| 16 | `COC_CATEGORY` | CHAR | 1 |  | Document Class |
| 17 | `OBJ_KEY` | CHAR | 20 |  | Object key |
| 18 | `DOC_TYPE` | CHAR | 2 |  | Document Type |
| 19 | `MAIN_TRANS` | CHAR | 4 |  | Main Transaction for Line Item |
| 20 | `SUB_TRANS` | CHAR | 4 |  | Subtransaction for Document Item |
| 21 | `NET_DATE` | DATS | 8 |  | Due date for net payment |
| 22 | `ITEM` | NUMC | 4 |  | Item number in contract account document |
| 23 | `COMP_CODE` | CHAR | 4 |  | Company Code |
| 24 | `BUSPARTNER` | CHAR | 10 |  | Business Partner Number |
| 25 | `CONT_ACCT` | CHAR | 12 |  | Contract Account Number |
| 26 | `CONTRACT` | CHAR | 20 |  | Reference Specifications from Contract |
| 27 | `AMOUNT` | DEC | 23 |  | Amount in Transaction Currency with +/- Sign |
| 28 | `AMOUNT_LOC_CURR` | DEC | 23 |  | Amount in Local Currency with +/- Signs |
| 29 | `DIVISION` | CHAR | 2 |  | Division |
| 30 | `STAT_KEY` | CHAR | 1 |  | Type of Statistical Line Item |
| 31 | `G_L_ACCT` | CHAR | 10 |  | General ledger account |
| 32 | `LOTYP` | CHAR | 2 |  | Lock Object Category |
| 33 | `PROID` | CHAR | 2 |  | Process Code (Example: Dunning, Payment) |
| 34 | `LOCKR` | CHAR | 1 |  | Lock Reason |
| 35 | `FDATE` | DATS | 8 |  | Move out date |
| 36 | `TDATE` | DATS | 8 |  | Lock valid to |
| 37 | `TFLAG` | CHAR | 1 |  | Text Update Flag |
| 38 | `UPDATEFLAG` | CHAR | 1 |  | Text Update Flag |
| 39 | `FINAL_POST` | DATS | 8 |  | Posting date of final bill |
