# ZISDM_DERIVE_RDG
**Description:** Derive Reading Table for Load Profile Billing
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `zisdm0201`
- `zisdm0201_main`
- `zisdm0201_sub_gp`
- `zisdm0201_sub_lp`
- `zisdm0204`
- `zisdm0205`
- `zisdm0206`
- `zisdm0235_sub`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ANLAGE` | CHAR | 10 |  | Installation |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 4 | `ADATSOLL_DERIVE_RDG` | DATS | 8 |  | Scheduled meter reading date |
| 5 | `ERROR` | CHAR | 100 |  | Error Message |
| 6 | `READING` | TTYP | 0 |  | Table Type for Reading table in Load Profile Billing |
