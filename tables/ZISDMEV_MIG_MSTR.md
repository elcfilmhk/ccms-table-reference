# ZISDMEV_MIG_MSTR
**Description:** Migration Master
**Total Fields:** 14
**Key Fields:** MANDT, VKONT, ANLAGE, VERTRAG, SERNR, ZWNUMMER, CREATION_TMP

## Programs Using This Table
- `zcl_isdm_evtou_mig_rpt`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 4 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 5 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 7 | `CREATION_TMP` | DEC | 15 | 🔑 | Time Stamp (Date and Time) |
| 8 | `OLD_TARIFTYP` | CHAR | 10 |  | Old Rate category |
| 9 | `NEW_TARIFTYP` | CHAR | 10 |  | New Rate category |
| 10 | `MIG_STATUS` | CHAR | 1 |  | Migration Status |
| 11 | `EFFECTIVE_DATE` | DATS | 8 |  | Migration Effective Date |
| 12 | `USERNAME` | CHAR | 12 |  | User name of the person responsible in change document |
| 13 | `MIG_EXE_DATE` | DATS | 8 |  | Date |
| 14 | `MIG_UZEIT` | TIMS | 6 |  | Time |
