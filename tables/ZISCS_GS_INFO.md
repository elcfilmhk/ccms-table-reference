# ZISCS_GS_INFO
**Description:** Government Subsidy Information
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_gs_info============ft`
- `z_cs_cxt_ca_list`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SCHEME_CAT` | CHAR | 10 |  | Scheme of Gov Subsidy |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `SCHEME` | CHAR | 10 |  | Scheme of Gov Subsidy |
| 4 | `SCHEME_EN` | CHAR | 50 |  | Government Subsidy Scheme English Description |
| 5 | `SCHEME_ZF` | CHAR | 50 |  | Government Subsidy Scheme Chinese Description |
| 6 | `ENTAMT` | CURR | 13 |  | Entitlement amount |
| 7 | `ENTUSG` | CURR | 13 |  | Entitlement usage |
| 8 | `FORFAMT` | CURR | 13 |  | Entitlement forfeiture amount |
| 9 | `BALENT` | CURR | 13 |  | Entitlement balance |
| 10 | `BEGDT` | DATS | 8 |  | From date |
| 11 | `ENDDT` | DATS | 8 |  | To date |
| 12 | `EXPIRY` | DATS | 8 |  | Expiry Date |
| 13 | `EXPIRY_TXT` | CHAR | 11 |  | Expiry Date |
