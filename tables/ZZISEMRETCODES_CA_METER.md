# ZZISEMRETCODES_CA_METER
**Description:** Customized structure for return code
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_mol_get_cons_profile===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TYPE` | CHAR | 1 |  | 'I'nfo; 'W'arning; 'E'rror |
| 2 | `RETURN_CODE` | CHAR | 100 |  | Return Code |
| 3 | `MESSAGE` | CHAR | 220 |  | Message Text |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `SERNR` | CHAR | 18 |  | Serial Number |
