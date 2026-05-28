# ZISCSMRINF
**Description:** Structure for MR information
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zcl_z_bapi_ca_mrinfo_g_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZCONTRACT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ZZPREMISE` | CHAR | 10 |  | Premise |
| 3 | `ZZINSTALLATION` | CHAR | 10 |  | Installation |
| 4 | `ZZSPARTE` | CHAR | 2 |  | Division |
| 5 | `ZZDEVICENO` | CHAR | 18 |  | Serial Number |
| 6 | `ZZREGISTER` | NUMC | 3 |  | Register |
| 7 | `ZZUOM` | CHAR | 6 |  | Unit of measurement for meter reading |
| 8 | `ZZPREDEC_NUM` | NUMC | 2 |  | Places before the decimal point in a register |
| 9 | `ZZPOSTDEC_NUM` | NUMC | 2 |  | Places after the decimal in a register |
| 10 | `ZZFUNKLAS` | CHAR | 8 |  | Function class |
