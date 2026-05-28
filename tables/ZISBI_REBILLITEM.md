# ZISBI_REBILLITEM
**Description:** Status for reverse and rebill program(item)
**Total Fields:** 11
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0260`
- `zisbi0263`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 3 | `ANLAGE` | CHAR | 10 |  | Installation |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `ERDAT` | DATS | 8 |  | Created on field from ZISBI_REBILLMASS table |
| 6 | `ERZEIT` | TIMS | 6 |  | Created At field from ZISBI_REBILLMASS table |
| 7 | `CHANGEDON` | DATS | 8 |  | Date of Last Change |
| 8 | `CHANGEDTIME` | TIMS | 6 |  | Modified time |
| 9 | `CHANGEDBY_PROG` | CHAR | 12 |  | Modified by (Program/Tcode) |
| 10 | `CHANGEDBY_USER` | CHAR | 12 |  | Modified by user ID |
| 11 | `BILL_ID` | CHAR | 2 |  | Bill ID |
