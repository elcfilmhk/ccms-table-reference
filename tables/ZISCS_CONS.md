# ZISCS_CONS
**Description:** Structure for consumption data
**Total Fields:** 22
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_consumption========ft`
- `z_bapi_mtreaddoc_cons_wa======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Structure for consumption data |
| 2 | `ZZCONTRACTACCNT` | CHAR | 12 |  | Contract Account Number |
| 3 | `ZZCONTRACT` | CHAR | 10 |  | Contract |
| 4 | `ZZPREMISE` | CHAR | 10 |  | Premise |
| 5 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 6 | `ZZDIVISION` | CHAR | 2 |  | Division |
| 7 | `ZZUOM` | CHAR | 6 |  | Unit of measurement for billing |
| 8 | `ZZCONS` | CHAR | 36 |  | Consumption |
| 9 | `ZZVALID_FROM` | DATS | 8 |  | Valid-From Date |
| 10 | `ZZVALID_TO` | DATS | 8 |  | Valid to date |
| 11 | `O_SUPPLY_E_STREET_3` | CHAR | 40 |  | Street 3 |
| 12 | `O_SUPPLY_E_STREET` | CHAR | 60 |  | Street |
| 13 | `O_SUPPLY_E_STREET_2` | CHAR | 40 |  | Street 2 |
| 14 | `O_SUPPLY_E_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 15 | `O_SUPPLY_E_REGION` | CHAR | 40 |  | City |
| 16 | `O_SUPPLY_E_DISTRICT` | CHAR | 40 |  | District |
| 17 | `O_SUPPLY_C_STREET_3` | CHAR | 40 |  | Street 3 |
| 18 | `O_SUPPLY_C_STREET` | CHAR | 60 |  | Street |
| 19 | `O_SUPPLY_C_STREET_2` | CHAR | 40 |  | Street 2 |
| 20 | `O_SUPPLY_C_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 21 | `O_SUPPLY_C_REGION` | CHAR | 40 |  | City |
| 22 | `O_SUPPLY_C_DISTRICT` | CHAR | 40 |  | District |
