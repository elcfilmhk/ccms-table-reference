# ZISCS_EEC_CHK_MKT_CONSENT_OUT
**Description:** Output structure for FM ZISCSEEC_CHECK_MKT_CONSENT
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zcl_ssr_program`
- `ziscs0807`
- `ziscs0807_test_radica`
- `ziscs1031`
- `ziscseec_check_mkt_consent====ft`
- `zrca_ssr_assign_upload`
- `zrca_ssr_cust_extract`
- `zrca_ssr_extract`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `EMAIL_ADDR` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 4 | `ALLOW_MKT` | CHAR | 1 |  | General Flag |
| 5 | `MKT_CONSENT` | CHAR | 1 |  | 'Y': Given; 'N': Rejected; others: Not Specified |
| 6 | `MKT_CONSENT_EFF_FM_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
