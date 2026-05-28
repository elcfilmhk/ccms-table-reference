# ZISCRMMYWSMPCAUR
**Description:** CRM My Workspace CA-User Mapping
**Total Fields:** 12
**Key Fields:** MANDT, SUB_NO, VKONT, POSNR

## Programs Using This Table
- `ziscrm0009`
- `ziscrm0010`
- `ziscrm0012`
- `ziscrm0031`
- `zisem_mol_highest_ca`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SUB_NO` | CHAR | 12 | 🔑 | Subscription number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `POSNR` | NUMC | 4 | 🔑 | Item number |
| 5 | `USERID` | CHAR | 50 |  | Web Login ID |
| 6 | `PARTNER` | CHAR | 17 |  | Partner number |
| 7 | `PLANID` | CHAR | 12 |  | Plan ID |
| 8 | `ERNAM` | CHAR | 12 |  | Created By |
| 9 | `CRTTS` | CHAR | 14 |  | Create timestamp |
| 10 | `CHUSER` | CHAR | 12 |  | Changed by |
| 11 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 12 | `CRT_EMAIL` | CHAR | 1 |  | Flag for new created email sent |
