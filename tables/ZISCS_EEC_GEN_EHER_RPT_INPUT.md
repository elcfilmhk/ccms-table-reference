# ZISCS_EEC_GEN_EHER_RPT_INPUT
**Description:** Input Structure for FM ZISCSEEC_GEN_EHER_RPT
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0390_eec`
- `ziscs0391_eec`
- `ziscseec_gen_eher_rpt=========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `EVAL_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 3 | `ISSUE_NO` | CHAR | 20 |  | Report Issue No |
| 4 | `EMAIL_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 5 | `LANGU` | LANG | 1 |  | Language in connection with the contract account |
