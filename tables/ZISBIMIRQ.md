# ZISBIMIRQ
**Description:** Welcome Letter Generation Request Table
**Total Fields:** 27
**Key Fields:** MANDT, BUDAT, EINZBELEG, SEQ_NO

## Programs Using This Table
- `z_isbi_sms_num_check==========ft`
- `zisbi0118`
- `zisbi0119`
- `zisbi0120`
- `zisbi0126`
- `ziscs0023`
- `ziscs0245`
- `zmoveindoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `EINZBELEG` | CHAR | 12 | 🔑 | Consecutive number of move-in document |
| 4 | `SEQ_NO` | CHAR | 2 | 🔑 | Sequence No |
| 5 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 6 | `TRANS_NO` | CHAR | 50 |  | Transaction no./Activity no for the MI shown |
| 7 | `SENDER` | CHAR | 50 |  | The Staff who create the MI |
| 8 | `EBILL_SENDER` | CHAR | 50 |  | Email sender address name |
| 9 | `EMAIL_ADDRESS1` | CHAR | 50 |  | EBill email 1 |
| 10 | `EMAIL_ADDRESS2` | CHAR | 50 |  | EBill email 2 |
| 11 | `EMAIL_ADDRESS3` | CHAR | 50 |  | EBill email 3 |
| 12 | `EMAIL_ADDRESS4` | CHAR | 50 |  | EBill email 4 |
| 13 | `EMAIL_ADDRESS5` | CHAR | 50 |  | EBill email 5 |
| 14 | `SMS_NO` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 15 | `SOURCE` | CHAR | 1 |  | Input source |
| 16 | `DISPATCH` | CHAR | 1 |  | Bill delivery channel |
| 17 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 18 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 19 | `CREATION_TIME` | TIMS | 6 |  | Creation Time |
| 20 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 21 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 22 | `MODIFIED_TIME` | TIMS | 6 |  | Modified Time |
| 23 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 24 | `PRINT_TIME` | TIMS | 6 |  | Printed time |
| 25 | `STATUS` | CHAR | 2 |  | Status 'F' - Fail or 'S' - Sent or 'M' - Missing,'H'-Supress |
| 26 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 27 | `SENDCONTROL_GP` | CHAR | 4 |  | Dispatch control for original customer |
