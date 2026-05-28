# ZISCS_EEC_EHER_OPT_INOUT_ROW
**Description:** Detail of eHER optin/optout date
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0386_eec`
- `ziscs0387_eec`
- `ziscs0393_eec`
- `ziscseec_eher_get_opt_inout===ft`
- `ziscseec_eher_set_opt_inout===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `EHER_OPT_IN_DATE` | DATS | 8 |  | CEP: e-HER Opt-In Date |
| 3 | `EHER_OPT_OUT_DAT` | DATS | 8 |  | CEP: e-HER Opt-Out Date |
| 4 | `EHER_OPT_OUT_REA` | CHAR | 4 |  | CEP: e-HER Opt-Out Reason |
| 5 | `HER_LANG` | CHAR | 1 |  | CEP: Home Energy Report (HER) Language |
