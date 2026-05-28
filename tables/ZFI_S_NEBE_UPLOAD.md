# ZFI_S_NEBE_UPLOAD
**Description:** NEBE upload
**Total Fields:** 25
**Key Fields:** _none_

## Programs Using This Table
- `z_fi_bapi_nebe_upload=========ft`
- `z_fi_nebe_upload==============ft`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `VERTRAG` | CHAR | 10 |  | Contract |
| 3 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 4 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 5 | `GL_TYPE` | CHAR | 4 |  | Data Type 4 Characters |
| 6 | `AMOUNT` | CHAR | 18 |  | Field length 18 |
| 7 | `POSTDATE` | CHAR | 10 |  | Character Field Length = 10 |
| 8 | `DUEDATE` | CHAR | 10 |  | Character Field Length = 10 |
| 9 | `ZONBILL` | CHAR | 1 |  | Present on the upcoming bill |
| 10 | `ZFINBILL` | CHAR | 1 |  | Unposted will include in final bill |
| 11 | `ZTXT` | CHAR | 20 |  | Text (20 Characters) |
| 12 | `AUFNR` | CHAR | 12 |  | Order Number |
| 13 | `MENGE` | CHAR | 18 |  | Field length 18 |
| 14 | `MEINS` | UNIT | 3 |  | Base Unit of Measure |
| 15 | `FLD01` | CHAR | 20 |  | Customer Field 1 |
| 16 | `FLD02` | CHAR | 20 |  | Customer Field 2 |
| 17 | `FLD03` | CHAR | 20 |  | Customer Field 3 |
| 18 | `FLD04` | CHAR | 20 |  | Customer Field 4 |
| 19 | `FLD05` | CHAR | 20 |  | Customer Field 5 |
| 20 | `FLD06` | CHAR | 20 |  | Customer Field 6 |
| 21 | `FLD07` | CHAR | 20 |  | Customer Field 7 |
| 22 | `FLD08` | CHAR | 20 |  | Customer Field 8 |
| 23 | `FLD09` | CHAR | 20 |  | Customer Field 9 |
| 24 | `FLD10` | CHAR | 20 |  | Customer Field 10 |
| 25 | `APPROVE` | CHAR | 1 |  | Character Field Length 1 |
