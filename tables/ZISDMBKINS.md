# ZISDMBKINS
**Description:** Customized table for bulk installation
**Total Fields:** 10
**Key Fields:** MANDT, ZZCODE, ZZRATECATEGORY, ZZRGCATEGORY, ZZRGTYPE, ZZRGUOM

## Programs Using This Table
- `zcl_isdm_evtou_mig_rpt`
- `zisdm0022_bulk`
- `zisdm0205`
- `zisdmupld`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZCODE` | CHAR | 2 | 🔑 | Meter Role Code |
| 3 | `ZZRATECATEGORY` | CHAR | 10 | 🔑 | Rate category |
| 4 | `ZZRGCATEGORY` | NUMC | 2 | 🔑 | Register category |
| 5 | `ZZRGTYPE` | CHAR | 2 | 🔑 | Register type |
| 6 | `ZZRGUOM` | CHAR | 6 | 🔑 | External Unit of Measurement in Technical Format (6-Char.) |
| 7 | `ZZRATETYPE` | CHAR | 8 |  | Rate Type |
| 8 | `ZZFACTGROUP` | CHAR | 10 |  | Rate fact group |
| 9 | `ZZBILLREL` | CHAR | 1 |  | Bill related installation allowed |
| 10 | `ZZNOBILLING` | CHAR | 1 |  | Not relevant to billing |
