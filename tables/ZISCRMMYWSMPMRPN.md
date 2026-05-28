# ZISCRMMYWSMPMRPN
**Description:** CRM My Workspace Meter-CA-Plan Mapping
**Total Fields:** 17
**Key Fields:** MANDT, SUB_NO, POSNR

## Programs Using This Table
- `ziscrm0010`
- `ziscrm0012`
- `ziscrm0015`
- `ziscrm0015a`
- `ziscrm0017`
- `ziscrm0017a`
- `ziscrm0018`
- `ziscrm0018a`
- `ziscrm0021`
- `ziscrm0031`
- `ziscrm0032`
- `ziscs0239`
- `zisdm0185`
- `zisdm0286`
- `zisdm0343`
- `zised0041`
- `zised0047`
- `zised0049`
- `zisem0003`
- `zisem0004`
- `zisem0005`
- `zismd0035`
- `zismd0035_nov17`
- `zismd0036`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SUB_NO` | CHAR | 12 | 🔑 | Subscription number |
| 3 | `POSNR` | NUMC | 4 | 🔑 | Item number |
| 4 | `VKONT_P` | CHAR | 12 |  | Contract Account Number |
| 5 | `SERNR` | CHAR | 18 |  | Meter Number |
| 6 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 7 | `PLANID` | CHAR | 12 |  | Plan ID |
| 8 | `APPDATE` | DATS | 8 |  | Application date |
| 9 | `STATUS` | CHAR | 2 |  | Status |
| 10 | `AMOUNT` | CURR | 13 |  | Amount |
| 11 | `ERNAM` | CHAR | 12 |  | Created By |
| 12 | `CRTTS` | CHAR | 14 |  | Create timestamp |
| 13 | `CHUSER` | CHAR | 12 |  | Changed by |
| 14 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 15 | `EFFDATE` | DATS | 8 |  | Effective date |
| 16 | `ENDDATE` | DATS | 8 |  | End date |
| 17 | `FC_LOC_CODE` | CHAR | 8 |  | Location of Forecast |
