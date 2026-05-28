# ZFI_NEBE_DISPLAY
**Description:** Structure for NEBE Online Posting Display screen
**Total Fields:** 35
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SORT` | NUMC | 2 |  | Sort Key |
| 2 | `ZSTATUS` | CHAR | 1 |  | Update status |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 5 | `BPNAME` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 6 | `VERTRAG` | CHAR | 10 |  | Contract |
| 7 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 8 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 9 | `DMBTR` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 10 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 11 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 12 | `ZONBILL` | CHAR | 1 |  | Present on the upcoming bill |
| 13 | `ZFINBILL` | CHAR | 1 |  | Unposted will include in final bill |
| 14 | `ZTXT` | CHAR | 20 |  | Text (20 Characters) |
| 15 | `CPUDT` | DATS | 8 |  | Date of entry |
| 16 | `ERNAM` | CHAR | 12 |  | Created By |
| 17 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 18 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 19 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 20 | `ZAPPDATE` | DATS | 8 |  | Date of approval |
| 21 | `ZAPPBY` | CHAR | 12 |  | Approver ID |
| 22 | `.INCLUDE` | &nbsp; | 0 |  | NEBE Customer Fields |
| 23 | `AUFNR` | CHAR | 12 |  | Order Number |
| 24 | `MENGE` | QUAN | 13 |  | Quantity |
| 25 | `MEINS` | UNIT | 3 |  | Base Unit of Measure |
| 26 | `FLD01` | CHAR | 20 |  | Customer Field 1 |
| 27 | `FLD02` | CHAR | 20 |  | Customer Field 2 |
| 28 | `FLD03` | CHAR | 20 |  | Customer Field 3 |
| 29 | `FLD04` | CHAR | 20 |  | Customer Field 4 |
| 30 | `FLD05` | CHAR | 20 |  | Customer Field 5 |
| 31 | `FLD06` | CHAR | 20 |  | Customer Field 6 |
| 32 | `FLD07` | CHAR | 20 |  | Customer Field 7 |
| 33 | `FLD08` | CHAR | 20 |  | Customer Field 8 |
| 34 | `FLD09` | CHAR | 20 |  | Customer Field 9 |
| 35 | `FLD10` | CHAR | 20 |  | Customer Field 10 |
