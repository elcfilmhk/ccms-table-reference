# ZISDM_BLOCKED_CONTRACT
**Description:** Structure of blocked contract for LPB billing block
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_lpb_billing_block======ft`
- `zisdm0200`
- `zisdm0201`
- `zisdm0201_main`
- `zisdm0201_sub_gp`
- `zisdm0201_sub_lp`
- `zisdm0205`
- `zisdm0206`
- `zisdm0235_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SOURCE_ANLAGE` | CHAR | 10 |  | Installation |
| 2 | `ANLAGE` | CHAR | 10 |  | Installation |
| 3 | `VERTRAG` | CHAR | 10 |  | Contract |
| 4 | `ERROR` | CHAR | 100 |  | Error Message |
