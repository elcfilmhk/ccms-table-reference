# ZZISCS_RANGES_STRING
**Description:** Structure for String-based Ranges
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_acb_get_ca_sms==============ft`
- `z_voltdip_send_reminder=======ft`
- `zcl_ziscseec_ep_trans__mpc`
- `zisbi0232`
- `zisbi0233`
- `zisbi0235`
- `ziscs0408`
- `ziscs0475_eec`
- `ziscs0714`
- `ziscs_eml_trk_ev_search=======ft`
- `ziscs_pon_export_ca`
- `ziscs_pon_get_ca==============ft`
- `ziscseec_ep_get_balance=======ft`
- `ziscseec_ep_get_balance_ws====ft`
- `ziscseec_ep_trans_search======ft`
- `ziscseec_ep_trans_search_ws===ft`
- `ziscseec_get_ca_attr==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SIGN` | CHAR | 1 |  | Type of SIGN component in row type of a Ranges type |
| 2 | `OPTION` | CHAR | 2 |  | Type of OPTION component in row type of a Ranges type |
| 3 | `LOW` | CHAR | 300 |  | Character 300 |
| 4 | `HIGH` | CHAR | 300 |  | Character 300 |
