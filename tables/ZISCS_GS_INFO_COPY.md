# ZISCS_GS_INFO_COPY
**Description:** Government Subsidy Information
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_gs_info_1==========ft`
- `z_bapi_get_gs_info_new========ft`
- `ziscs0860`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SCHEME_CAT` | CHAR | 10 |  | Scheme of Gov Subsidy |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `SCHEME` | CHAR | 10 |  | Scheme of Gov Subsidy |
| 4 | `ENTAMT` | CURR | 13 |  | Entitlement amount |
| 5 | `ENTUSG` | CURR | 13 |  | Entitlement usage |
| 6 | `FORFAMT` | CURR | 13 |  | Entitlement forfeiture amount |
| 7 | `BALENT` | CURR | 13 |  | Entitlement balance |
| 8 | `BEGDT` | DATS | 8 |  | From date |
| 9 | `ENDDT` | DATS | 8 |  | To date |
| 10 | `EXPIRY` | DATS | 8 |  | Expiry Date |
| 11 | `EXPIRY_TXT` | CHAR | 11 |  | Expiry Date |
| 12 | `SUPPLEMENTARY_SUB` | CURR | 13 |  | Entitlement amount |
