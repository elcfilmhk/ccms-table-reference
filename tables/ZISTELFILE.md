# ZISTELFILE
**Description:** Save Phone data from Local pc file temporary
**Total Fields:** 9
**Key Fields:** MANDT, SEQ

## Programs Using This Table
- `ziscrm0310`
- `ziscrm0310_submit`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQ` | NUMC | 10 | 🔑 | File Sequence |
| 3 | `BP` | CHAR | 10 |  | Business Partner Number |
| 4 | `TYPE` | CHAR | 6 |  | Character field of length 6 |
| 5 | `PHONE` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 6 | `EXTENS` | CHAR | 10 |  | Telephone no.: Extension |
| 7 | `ZDEFAULT` | CHAR | 1 |  | Single-Character Flag |
| 8 | `COUNTRY` | CHAR | 3 |  | Country for telephone/fax number |
| 9 | `FILENAME` | CHAR | 255 |  | File name |
