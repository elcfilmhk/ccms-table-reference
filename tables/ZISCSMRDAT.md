# ZISCSMRDAT
**Description:** Structure for MR Date information
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_all_account_info=======ft`
- `z_bapi_mr_nextreadcycle=======ft`
- `zcl_z_bapi_all_account_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZCONTRACT_ACCNT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ZZCONTRACT` | CHAR | 10 |  | Contract |
| 3 | `ZZPREMISE` | CHAR | 10 |  | Premise |
| 4 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 5 | `ZZDIVISION` | CHAR | 2 |  | Division |
| 6 | `ZZMRU` | CHAR | 8 |  | Meter Reading Unit |
| 7 | `ZZMRDATE` | DATS | 8 |  | Date |
| 8 | `ZZMRREASON` | CHAR | 2 |  | Meter reading reason |
| 9 | `ZZALTPORTION` | CHAR | 8 |  | Alternative portion |
| 10 | `ZZMRUPORTION` | CHAR | 8 |  | Portion |
