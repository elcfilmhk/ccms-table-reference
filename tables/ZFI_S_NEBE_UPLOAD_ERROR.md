# ZFI_S_NEBE_UPLOAD_ERROR
**Description:** NEBE Upload Error
**Total Fields:** 27
**Key Fields:** _none_

## Programs Using This Table
- `z_fi_bapi_nebe_upload=========ft`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | NEBE upload |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `VERTRAG` | CHAR | 10 |  | Contract |
| 4 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 5 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 6 | `GL_TYPE` | CHAR | 4 |  | Data Type 4 Characters |
| 7 | `AMOUNT` | CHAR | 18 |  | Field length 18 |
| 8 | `POSTDATE` | CHAR | 10 |  | Character Field Length = 10 |
| 9 | `DUEDATE` | CHAR | 10 |  | Character Field Length = 10 |
| 10 | `ZONBILL` | CHAR | 1 |  | Present on the upcoming bill |
| 11 | `ZFINBILL` | CHAR | 1 |  | Unposted will include in final bill |
| 12 | `ZTXT` | CHAR | 20 |  | Text (20 Characters) |
| 13 | `AUFNR` | CHAR | 12 |  | Order Number |
| 14 | `MENGE` | CHAR | 18 |  | Field length 18 |
| 15 | `MEINS` | UNIT | 3 |  | Base Unit of Measure |
| 16 | `FLD01` | CHAR | 20 |  | Customer Field 1 |
| 17 | `FLD02` | CHAR | 20 |  | Customer Field 2 |
| 18 | `FLD03` | CHAR | 20 |  | Customer Field 3 |
| 19 | `FLD04` | CHAR | 20 |  | Customer Field 4 |
| 20 | `FLD05` | CHAR | 20 |  | Customer Field 5 |
| 21 | `FLD06` | CHAR | 20 |  | Customer Field 6 |
| 22 | `FLD07` | CHAR | 20 |  | Customer Field 7 |
| 23 | `FLD08` | CHAR | 20 |  | Customer Field 8 |
| 24 | `FLD09` | CHAR | 20 |  | Customer Field 9 |
| 25 | `FLD10` | CHAR | 20 |  | Customer Field 10 |
| 26 | `APPROVE` | CHAR | 1 |  | Character Field Length 1 |
| 27 | `MSG` | CHAR | 500 |  | Customer Text (500) Field |
