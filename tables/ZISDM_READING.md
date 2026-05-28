# ZISDM_READING
**Description:** Structure for Reading table in Load Profile Billing
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_lpb_derive_load_profileft`
- `z_isdm_lpb_derive_rdg_from_lp=ft`
- `zisdm0201`
- `zisdm0201_main`
- `zisdm0201_sub_gp`
- `zisdm0201_sub_lp`
- `zisdm0205`
- `zisdm0235_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 2 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 3 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 4 | `ABLHINW` | CHAR | 4 |  | Note from meter reader |
| 5 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 6 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 7 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 8 | `ORG_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 9 | `REV_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 10 | `ORG_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 11 | `REV_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 12 | `RDG_NOCHG_IND` | CHAR | 1 |  | Reading no change indicator |
