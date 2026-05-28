# ZISCS_EEC_EML_RCPT_ROW
**Description:** Row of email Recipient
**Total Fields:** 2
**Key Fields:** _none_

## Programs Using This Table
- `ziscseec_queue_email==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `RCPT_TY` | CHAR | 4 |  | 'TO' / 'CC' / 'BCC' |
| 2 | `RCPT_EML_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
