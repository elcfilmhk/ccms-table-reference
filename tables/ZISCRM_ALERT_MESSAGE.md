# ZISCRM_ALERT_MESSAGE
**Description:** Alert Message
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `zaccount`
- `zalertmsg`
- `zmoveindoc`
- `zpartner`
- `zpremises`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BP` | CHAR | 10 |  | Business Partner Number |
| 2 | `CA` | CHAR | 12 |  | Contract Account Number |
| 3 | `SEQ_NO` | NUMC | 6 |  | Alert Sequence Number |
| 4 | `VALID_FROM` | DATS | 8 |  | Alert Effective Date |
| 5 | `VALID_TO` | DATS | 8 |  | Alert Expiry Date |
| 6 | `SHORT_TEXT` | CHAR | 70 |  | Alert Message Short Text |
| 7 | `LONG_TEXT_1` | CHAR | 70 |  | Alert Message Long Text 1 |
| 8 | `LONG_TEXT_2` | CHAR | 70 |  | Alert Message Long Text 2 |
| 9 | `LONG_TEXT_3` | CHAR | 70 |  | Alert Message Long Text 3 |
