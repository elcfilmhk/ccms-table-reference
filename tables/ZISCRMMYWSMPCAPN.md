# ZISCRMMYWSMPCAPN
**Description:** CRM My Workspace CA-Plan Mapping
**Total Fields:** 16
**Key Fields:** MANDT, SUB_NO, POSNR

## Programs Using This Table
- `ziscrm0009`
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
- `zisem_mol_highest_ca`
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
| 5 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 6 | `PLANID` | CHAR | 12 |  | Plan ID |
| 7 | `APPDATE` | DATS | 8 |  | Application date |
| 8 | `STATUS` | CHAR | 2 |  | Status |
| 9 | `AMOUNT` | CURR | 13 |  | Amount |
| 10 | `ERNAM` | CHAR | 12 |  | Created By |
| 11 | `CRTTS` | CHAR | 14 |  | Create timestamp |
| 12 | `CHUSER` | CHAR | 12 |  | Changed by |
| 13 | `MDFTS` | CHAR | 14 |  | Modified timestamp |
| 14 | `EFFDATE` | DATS | 8 |  | Effective date |
| 15 | `ENDDATE` | DATS | 8 |  | End date |
| 16 | `FC_LOC_CODE` | CHAR | 8 |  | Location of Forecast |
