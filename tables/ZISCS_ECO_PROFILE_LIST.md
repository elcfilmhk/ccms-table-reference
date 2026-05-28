# ZISCS_ECO_PROFILE_LIST
**Description:** Output structure of FM "Z_BAPI_MULTI_ECODATA_PROFILE"
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_multi_ecodata_profile==ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ECO_POINTS` | INT4 | 10 |  | Eco Points Transaction Amount (+: award to CA; -: deduct) |
| 3 | `IS_AMI` | CHAR | 1 |  | AMI |
| 4 | `AUTOPAY` | CHAR | 1 |  | Autopay Flag |
| 5 | `GREENBILL` | CHAR | 1 |  | Green bill flag |
| 6 | `PRODUCT_CODE` | CHAR | 100 |  | Product_code |
