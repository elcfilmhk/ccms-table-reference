# ZZISEM_CONS_PROFILE
**Description:** Output of FM Z_ISDM_MOL_GET_CONS_PROFILE
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_mol_get_cons_profile===ft`
- `zisdm0286`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `PROFILE` | NUMC | 18 |  | Number of EDM Profile |
| 4 | `DATE` | DATS | 8 |  | From-Date |
| 5 | `HOUR` | NUMC | 4 |  | From-Hour |
| 6 | `TIME` | TIMS | 6 |  | From-time |
| 7 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
| 8 | `VALUE` | DEC | 31 |  | Profile value at application level |
