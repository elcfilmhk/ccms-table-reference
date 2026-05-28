# ZISCRMMYWSMPMRUR
**Description:** CRM My Workspace Meter-User Mapping
**Total Fields:** 13
**Key Fields:** MANDT, SUB_NO, SERNR, VKONT, POSNR

## Programs Using This Table
- `ziscrm0010`
- `ziscrm0012`
- `ziscrm0031`
- `zisem0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SUB_NO` | CHAR | 12 | 🔑 | Subscription number |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Meter Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `POSNR` | NUMC | 4 | 🔑 | Item number |
| 6 | `USERID` | CHAR | 50 |  | Web Login ID |
| 7 | `PARTNER` | CHAR | 17 |  | Partner number |
| 8 | `PLANID` | CHAR | 12 |  | Plan ID |
| 9 | `ERNAM` | CHAR | 12 |  | Created By |
| 10 | `CRTTS` | CHAR | 14 |  | Create timestamp |
| 11 | `CHUSER` | CHAR | 12 |  | Changed by |
| 12 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 13 | `CRT_EMAIL` | CHAR | 1 |  | Flag for new created email sent |
