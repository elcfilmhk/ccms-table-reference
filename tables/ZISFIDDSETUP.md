# ZISFIDDSETUP
**Description:** New Direct Debit Setup Accounts
**Total Fields:** 17
**Key Fields:** MANDT, OBJECTCLAS, OBJECTID, CHANGENR, TABNAME, TABKEY, FNAME

## Programs Using This Table
- `ziscs0212`
- `zisfi0157`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJECTCLAS` | CHAR | 15 | 🔑 | Object class |
| 3 | `OBJECTID` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `CHANGENR` | CHAR | 10 | 🔑 | Change Number of Document |
| 5 | `TABNAME` | CHAR | 30 | 🔑 | Table Name |
| 6 | `TABKEY` | CHAR | 70 | 🔑 | Changed table record key |
| 7 | `FNAME` | CHAR | 30 | 🔑 | Field Name |
| 8 | `VALUE_NEW` | CHAR | 254 |  | New contents of changed field |
| 9 | `VALUE_OLD` | CHAR | 254 |  | Old contents of changed field |
| 10 | `UDATE` | DATS | 8 |  | Creation date of the change document |
| 11 | `UTIME` | TIMS | 6 |  | Time changed |
| 12 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 13 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 14 | `BLART` | CHAR | 2 |  | Document Type |
| 15 | `ZALDT` | DATS | 8 |  | Posting date of the payment document |
| 16 | `RWBTR` | CURR | 13 |  | Amount Paid in the Payment Currency |
| 17 | `SEGMENT_LABEL` | CHAR | 1 |  | Segment label |
