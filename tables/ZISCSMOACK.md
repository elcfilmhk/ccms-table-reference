# ZISCSMOACK
**Description:** MO Acknowledgement Request Table
**Total Fields:** 20
**Key Fields:** MANDT, BUDAT, AUSZBELEG

## Programs Using This Table
- `zisbi0120`
- `zisbi0131`
- `ziscs0184`
- `ziscs0298`
- `ziscs0436`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUDAT` | DATS | 8 | 🔑 | Posting Date in the Document |
| 3 | `AUSZBELEG` | CHAR | 12 | 🔑 | Consecutive number of move-out document |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `TRANS_NO` | CHAR | 50 |  | Transaction no./Activity no for the MI shown |
| 6 | `SENDER` | CHAR | 50 |  | The Staff who create the MI |
| 7 | `EBILL_SENDER` | CHAR | 50 |  | MO Acknowledgement Request Sender Email Address |
| 8 | `EMAIL_ADDRESS` | CHAR | 50 |  | MO Acknowledgement Request Recipient Email address |
| 9 | `MOBILE_NO` | CHAR | 8 |  | MO Acknowledgement Request Mobile Number |
| 10 | `DISPATCH` | CHAR | 1 |  | Delivery Channel |
| 11 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 12 | `CREATION_TIME` | TIMS | 6 |  | Creation time |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 15 | `MODIFIED_TIME` | TIMS | 6 |  | Modified time |
| 16 | `DRUCKDAT` | DATS | 8 |  | Print Date |
| 17 | `VSTELLE` | CHAR | 10 |  | Premise |
| 18 | `PRINT_TIME` | TIMS | 6 |  | Printed time |
| 19 | `STATUS` | CHAR | 2 |  | MO Acknowledgement Request Status |
| 20 | `REVERSE_MO` | CHAR | 1 |  | Reverse MO flag |
