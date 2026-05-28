# ZFI_NEBE_CANCEL
**Description:** Structure for NEBE Online Posting Cancellation screen
**Total Fields:** 20
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 2 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 5 | `CPUDT` | DATS | 8 |  | Date of entry |
| 6 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 7 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 8 | `BPNAME` | CHAR | 40 |  | Last Name of Business Partner (Person) |
| 9 | `VERTRAG` | CHAR | 10 |  | Contract |
| 10 | `DMBTR` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 11 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 12 | `ZSTATUS` | CHAR | 1 |  | Update status |
| 13 | `ZAPPSTAT` | CHAR | 1 |  | Approval status for manual creation |
| 14 | `ZAPPDESC` | CHAR | 35 |  | Approval Status |
| 15 | `ZONBILL` | CHAR | 1 |  | Present on the upcoming bill |
| 16 | `ZFINBILL` | CHAR | 1 |  | Unposted will include in final bill |
| 17 | `ZTXT` | CHAR | 20 |  | Text (20 Characters) |
| 18 | `ERNAM` | CHAR | 12 |  | Created By |
| 19 | `SELECTED` | CHAR | 1 |  | Entry selected |
| 20 | `UNSAVE` | CHAR | 1 |  | Record is unsaved |
