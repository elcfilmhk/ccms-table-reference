# ZISBIRBI77
**Description:** Temporary table to store RFBI77
**Total Fields:** 26
**Key Fields:** MANDT, DATEFROM, DATETO, BILLDOC, CONTRACTACC, CONTRACT, PARTNER

## Programs Using This Table
- `zisbi0031`
- `zisbi0047`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATEFROM` | DATS | 8 | 🔑 | Date |
| 3 | `DATETO` | DATS | 8 | 🔑 | Date |
| 4 | `BILLDOC` | CHAR | 12 | 🔑 | Number of a billing document |
| 5 | `CONTRACTACC` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `CONTRACT` | CHAR | 10 | 🔑 | Contract |
| 7 | `PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 8 | `CREATIONDATE` | DATS | 8 |  | Creation date of billing document |
| 9 | `BILLTYPE` | CHAR | 2 |  | Billing Transaction |
| 10 | `ACCCLASS` | CHAR | 4 |  | Account class |
| 11 | `ANLAGE` | CHAR | 10 |  | Installation |
| 12 | `FIRSTIND` | CHAR | 1 |  | Single-Character Flag |
| 13 | `CHILDIND` | CHAR | 1 |  | Single-Character Flag |
| 14 | `BPTYPE` | CHAR | 4 |  | Business Partner Type |
| 15 | `BPNAME` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 16 | `RATECATEGORY` | CHAR | 10 |  | Rate category |
| 17 | `NETAMOUNT` | CURR | 13 |  | Net amount of billing line item |
| 18 | `KWHONCONSUMP` | DEC | 31 |  | Billing quantity for internal billing format |
| 19 | `KWHOFFCONSUMP` | DEC | 31 |  | Billing quantity for internal billing format |
| 20 | `KVAONCONSUMP` | DEC | 31 |  | Billing quantity for internal billing format |
| 21 | `KVAOFFCONSUMP` | DEC | 31 |  | Billing quantity for internal billing format |
| 22 | `STREET1` | CHAR | 40 |  | Street 3 |
| 23 | `STREET2` | CHAR | 40 |  | Street 2 |
| 24 | `STREET3` | CHAR | 40 |  | Street 3 |
| 25 | `DISTRICT` | CHAR | 40 |  | District |
| 26 | `CITY` | CHAR | 40 |  | City |
