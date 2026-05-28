# ZISDM_LP_BILL_REGISTER
**Description:** Table structure for Z_ISDM_GET_BILL_LP_REG
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_get_bill_lp_reg========ft`
- `zed_aggregate_lp==============ft`
- `zed_get_profl_from_cont_acc===ft`
- `zisdm0207`
- `zisdm0209`
- `zisdm0209_ev`
- `zisdm0231`
- `zisdm0241`
- `zisdm0241_sub`
- `zisdm0241n`
- `zisdm0284`
- `zisdm0286`
- `zisdm0310_adr`
- `zisdm0333`
- `zisdm0343`
- `zised0008`
- `zised0016`
- `zised0017`
- `zised0049`
- `zisem0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ANLAGE` | CHAR | 10 |  | Installation |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 4 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 5 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 6 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 7 | `TARIFART` | CHAR | 8 |  | Rate Type |
| 8 | `STARTDATE` | DATS | 8 |  | Date |
| 9 | `ENDDATE` | DATS | 8 |  | Date |
| 10 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 11 | `MTR_STATUS` | CHAR | 1 |  | Meter status |
| 12 | `MAININST` | CHAR | 10 |  | Installation |
