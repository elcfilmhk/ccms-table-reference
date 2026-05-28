# ZISFINEBEITEM
**Description:** Posting Request for NEBE Item
**Total Fields:** 40
**Key Fields:** MANDT, HVORG, TVORG, VKONT, BUDAT, CPUDT, CPUTM

## Programs Using This Table
- `z_cs_cxt_post_oa`
- `z_fi_bapi_nebe_upload=========ft`
- `zisbi0132`
- `zisbi0133`
- `zisbi0209`
- `zisbi0271`
- `ziscrm0010`
- `ziscrm0020`
- `ziscrm0021`
- `ziscrm0031`
- `ziscs0239`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`
- `zisfi0197`
- `zisfi0197_smis`
- `zisfi0210`
- `zisfi0261`
- `zisfi0262`
- `zisfi0263`
- `zisfi0314`
- `zissd00065`
- `zissd00090`
- `zissd00092`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 6 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 7 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 8 | `ZSTATUS` | CHAR | 1 |  | Update status |
| 9 | `VERTRAG` | CHAR | 10 |  | Contract |
| 10 | `DMBTR` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 11 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 12 | `ERNAM` | CHAR | 12 |  | Created By |
| 13 | `ZTXT` | CHAR | 20 |  | Text (20 Characters) |
| 14 | `ZSOURCE` | CHAR | 1 |  | Input Source |
| 15 | `ZONBILL` | CHAR | 1 |  | Present on the upcoming bill |
| 16 | `ZFINBILL` | CHAR | 1 |  | Unposted will include in final bill |
| 17 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 18 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 19 | `OPBEL` | CHAR | 12 |  | Document Number in Contract Accounts Receivable and Payable |
| 20 | `TEXT` | CHAR | 73 |  | Message Text |
| 21 | `ZAPPSTAT` | CHAR | 1 |  | Approval status for manual creation |
| 22 | `ZAPPDATE` | DATS | 8 |  | Date of approval |
| 23 | `ZAPPTIME` | TIMS | 6 |  | Time of approval |
| 24 | `ZAPPBY` | CHAR | 12 |  | Approver ID |
| 25 | `SPART` | CHAR | 2 |  | Division |
| 26 | `KOSTL` | CHAR | 10 |  | Cost Center |
| 27 | `.INCLUDE` | &nbsp; | 0 |  | NEBE Customer Fields |
| 28 | `AUFNR` | CHAR | 12 |  | Order Number |
| 29 | `MENGE` | QUAN | 13 |  | Quantity |
| 30 | `MEINS` | UNIT | 3 |  | Base Unit of Measure |
| 31 | `FLD01` | CHAR | 20 |  | Customer Field 1 |
| 32 | `FLD02` | CHAR | 20 |  | Customer Field 2 |
| 33 | `FLD03` | CHAR | 20 |  | Customer Field 3 |
| 34 | `FLD04` | CHAR | 20 |  | Customer Field 4 |
| 35 | `FLD05` | CHAR | 20 |  | Customer Field 5 |
| 36 | `FLD06` | CHAR | 20 |  | Customer Field 6 |
| 37 | `FLD07` | CHAR | 20 |  | Customer Field 7 |
| 38 | `FLD08` | CHAR | 20 |  | Customer Field 8 |
| 39 | `FLD09` | CHAR | 20 |  | Customer Field 9 |
| 40 | `FLD10` | CHAR | 20 |  | Customer Field 10 |
