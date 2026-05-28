# ZISDM_EV_TOU_MIG_OUTPUT_STR
**Description:** EV TOU Migration Structure
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `zcl_isdm_evtou_mig_rpt`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `ANLAGE` | CHAR | 10 |  | Installation |
| 3 | `VERTRAG` | CHAR | 10 |  | Contract |
| 4 | `SERNR` | CHAR | 18 |  | Serial Number |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `OLD_TARIFTYP` | CHAR | 10 |  | Old Rate category |
| 7 | `NEW_TARIFTYP` | CHAR | 10 |  | New Rate category |
| 8 | `EFFECTIVE_DATE` | DATS | 8 |  | Migration effective date |
| 9 | `MIG_STATUS` | CHAR | 1 |  | Migration Status |
| 10 | `EINZDAT_ASSIGN_SPECIAL` | CHAR | 1 |  | Boolean Variable (X=true, -=false, space=unknown) |
| 11 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 12 | `MESSAGE` | CHAR | 220 |  | Message |
