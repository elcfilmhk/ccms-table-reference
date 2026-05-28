# ZISDMUSAGEALTHIS
**Description:** Alert Sent Table
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, ADATSOLL, DETAIL

## Programs Using This Table
- `zisdm0278`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 4 | `DETAIL` | CHAR | 10 | 🔑 | Details of the eService type |
| 5 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 6 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 7 | `SMS` | CHAR | 255 |  | SMS |
