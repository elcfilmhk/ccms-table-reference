# ZISMDPENDMSUBACC
**Description:** Sub Account SP Channel without Master Account SP Channel
**Total Fields:** 14
**Key Fields:** MANDT, ANLAGE, SP_CHANNEL_NO, SERNR, ZWNUMMER

## Programs Using This Table
- `zismd0007`
- `zismd0025`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SP_CHANNEL_NO` | NUMC | 10 | 🔑 | Service Point Channel Number |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 6 | `ASPC_EFF_DATE` | DATS | 8 |  | Service Point Link effective start date |
| 7 | `CHANNEL_NO` | NUMC | 6 |  | Channel number of the Account Channel |
| 8 | `EFF_START_DATE` | DATS | 8 |  | Account Channel effective start date |
| 9 | `TARIFART` | CHAR | 8 |  | Rate Type |
| 10 | `CHARGE_TYPE` | CHAR | 10 |  | Charge Type of the Account Channel |
| 11 | `ACC_LINK_ID` | CHAR | 10 |  | Installation |
| 12 | `ACL_EFF_DATE` | DATS | 8 |  | Account Link Effective Date |
| 13 | `TASK_OPERATION` | CHAR | 10 |  | Task Operation |
| 14 | `PROCESSED` | CHAR | 1 |  | Processed Indicator |
