# ZISCSCONS
**Description:** Structure for consumption data
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_mtreaddoc_cons=========ft`
- `zcl_z_clp_online2_01_mpc`
- `zcl_z_clp_online_demo_mpc`
- `zisdm0067`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZCONTRACTACCNT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ZZCONTRACT` | CHAR | 10 |  | Contract |
| 3 | `ZZPREMISE` | CHAR | 10 |  | Premise |
| 4 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 5 | `ZZDIVISION` | CHAR | 2 |  | Division |
| 6 | `ZZUOM` | CHAR | 6 |  | Unit of measurement for billing |
| 7 | `ZZCONS` | CHAR | 36 |  | Consumption |
| 8 | `ZZVALID_FROM` | DATS | 8 |  | Valid-From Date |
| 9 | `ZZVALID_TO` | DATS | 8 |  | Valid to date |
