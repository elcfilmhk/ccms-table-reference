# ZFI_NEBEITEM_N
**Description:** Structure for new NEBE items maintenance
**Total Fields:** 42
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 3 | `BPNAME` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 4 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 5 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 6 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 7 | `CPUDT` | DATS | 8 |  | Date of entry |
| 8 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 9 | `ZSTATUS` | CHAR | 1 |  | Update status |
| 10 | `VERTRAG` | CHAR | 10 |  | Contract |
| 11 | `ZZSEQNO` | NUMC | 4 |  | Sequence Num. |
| 12 | `GL_DESC` | CHAR | 30 |  | Text |
| 13 | `DMBTR` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 14 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 15 | `ERNAM` | CHAR | 12 |  | Created By |
| 16 | `ZTXT` | CHAR | 20 |  | Text (20 Characters) |
| 17 | `ZSOURCE` | CHAR | 1 |  | Input Source |
| 18 | `ZONBILL` | CHAR | 1 |  | Present on the upcoming bill |
| 19 | `ZFINBILL` | CHAR | 1 |  | Unposted will include in final bill |
| 20 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 21 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 22 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 23 | `TEXT` | CHAR | 73 |  | Message Text |
| 24 | `ZAPPSTAT` | CHAR | 1 |  | Approval status for manual creation |
| 25 | `ZAPPDATE` | DATS | 8 |  | Date of approval |
| 26 | `ZAPPTIME` | TIMS | 6 |  | Time of approval |
| 27 | `ZAPPBY` | CHAR | 12 |  | Approver ID |
| 28 | `SELECTED` | CHAR | 1 |  | Entry selected |
| 29 | `.INCLUDE` | &nbsp; | 0 |  | NEBE Customer Fields |
| 30 | `AUFNR` | CHAR | 12 |  | Order Number |
| 31 | `MENGE` | QUAN | 13 |  | Quantity |
| 32 | `MEINS` | UNIT | 3 |  | Base Unit of Measure |
| 33 | `FLD01` | CHAR | 20 |  | Customer Field 1 |
| 34 | `FLD02` | CHAR | 20 |  | Customer Field 2 |
| 35 | `FLD03` | CHAR | 20 |  | Customer Field 3 |
| 36 | `FLD04` | CHAR | 20 |  | Customer Field 4 |
| 37 | `FLD05` | CHAR | 20 |  | Customer Field 5 |
| 38 | `FLD06` | CHAR | 20 |  | Customer Field 6 |
| 39 | `FLD07` | CHAR | 20 |  | Customer Field 7 |
| 40 | `FLD08` | CHAR | 20 |  | Customer Field 8 |
| 41 | `FLD09` | CHAR | 20 |  | Customer Field 9 |
| 42 | `FLD10` | CHAR | 20 |  | Customer Field 10 |
