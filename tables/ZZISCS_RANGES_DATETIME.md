# ZZISCS_RANGES_DATETIME
**Description:** Structure for Datetime-based Ranges
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_voltdip_send_reminder=======ft`
- `zcl_ziscseec_ep_trans__mpc`
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`
- `ziscs0714`
- `ziscs_eml_trk_ev_search=======ft`
- `ziscseec_ep_trans_search======ft`
- `ziscseec_ep_trans_search_ws===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SIGN` | CHAR | 1 |  | Type of SIGN component in row type of a Ranges type |
| 2 | `OPTION` | CHAR | 2 |  | Type of OPTION component in row type of a Ranges type |
| 3 | `LOW` | CHAR | 14 |  | Call date/time received |
| 4 | `HIGH` | CHAR | 14 |  | Call date/time received |
