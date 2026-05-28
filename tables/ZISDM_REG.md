# ZISDM_REG
**Description:** Cust. structure for FM Z_ISDM_GET_METER_REL
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_comp_meter_reg=========ft`
- `z_isdm_get_meter_reg==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `GERNR` | CHAR | 18 |  | Serial Number |
| 2 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 3 | `ZWGRUPPE` | CHAR | 8 |  | Register Group |
| 4 | `ZWTYP` | NUMC | 2 |  | Register category |
| 5 | `ZWART` | CHAR | 2 |  | Register type |
| 6 | `NABLESEN` | CHAR | 1 |  | Do Not Read Register |
| 7 | `MASSREAD` | UNIT | 3 |  | Unit of measurement for meter reading |
| 8 | `INTSIZEID` | CHAR | 4 |  | Interval Length ID |
| 9 | `BLIWIRK` | NUMC | 2 |  | Reactive, apparent, or active registers |
