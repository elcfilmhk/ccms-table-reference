# ZZISEDSTRUCTPROF
**Description:** Structure for FM ZED_GET_PROFL_FROM_CONT_ACC output
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0207`
- `zisdm0231`
- `zisdm0284`
- `zisdm0286`
- `zisdm0310_adr`
- `zisdm0333`
- `zisdm0343`
- `zised0008`
- `zised0017`
- `zised0049`
- `zisem0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 3 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 4 | `ANLAGE` | CHAR | 10 |  | Installation |
| 5 | `DATEFROM` | DATS | 8 |  | Field of type DATS |
| 6 | `DATETO` | DATS | 8 |  | Field of type DATS |
