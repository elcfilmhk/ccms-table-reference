# ZISBINEBEHDR
**Description:** NEBE Bill Generation Request Detail Table
**Total Fields:** 33
**Key Fields:** MANDT, OPBEL

## Programs Using This Table
- `zisbi0116`
- `ziscrm0010`
- `ziscrm0020`
- `ziscrm0031`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OPBEL` | CHAR | 12 | 🔑 | NEBE document number |
| 3 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `CHARGE_TYPE` | CHAR | 3 |  | Charge type |
| 6 | `VKONT_DESC` | CHAR | 30 |  | CA description |
| 7 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 8 | `REF_NO` | CHAR | 20 |  | Reference no. |
| 9 | `MERCH_CODE` | CHAR | 2 |  | Bill type & Merchant code |
| 10 | `SOURCE` | CHAR | 1 |  | Input source |
| 11 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 12 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 13 | `LANGU` | LANG | 1 |  | Bill language |
| 14 | `TOTAL_AMNT` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 15 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 16 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 17 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 18 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 19 | `BARCODE_IND` | CHAR | 1 |  | Suppress barcode indicator |
| 20 | `BILLNAME` | CHAR | 40 |  | Bill name |
| 21 | `STATUS` | CHAR | 1 |  | Status N -New or G - Generate or C V Cancel |
| 22 | `BPNAME` | CHAR | 40 |  | Recipient name |
| 23 | `ADD_LANGU` | LANG | 1 |  | Address language |
| 24 | `ADDRESSLINE1` | CHAR | 40 |  | Address line 1 |
| 25 | `ADDRESSLINE2` | CHAR | 40 |  | Address line 2 |
| 26 | `ADDRESSLINE3` | CHAR | 40 |  | Address line 3 |
| 27 | `ADDRESSLINE4` | CHAR | 40 |  | Address line 4 |
| 28 | `ADDRESSLINE5` | CHAR | 40 |  | Address line 5 |
| 29 | `CPERSON` | CHAR | 40 |  | Contact Person |
| 30 | `HEADER_DESC1` | CHAR | 28 |  | Header description 1 |
| 31 | `HEADER1` | CHAR | 28 |  | Header 1 |
| 32 | `HEADER_DESC2` | CHAR | 28 |  | Header description 2 |
| 33 | `HEADER2` | CHAR | 28 |  | Header 2 |
