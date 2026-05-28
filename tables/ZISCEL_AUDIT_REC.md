# ZISCEL_AUDIT_REC
**Description:** Audit transaction record
**Total Fields:** 21
**Key Fields:** MANDT, VKONT, AUD_YEAR, AUD_CRE_DAT, AUD_CRE_TIM

## Programs Using This Table
- `ziscs0400`
- `ziscs0420`
- `ziscs0430`
- `ziscs0435`
- `ziscs0440`
- `ziscs0441`
- `ziscs0442`
- `ziscs0443`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `AUD_YEAR` | CHAR | 4 | 🔑 | Audit year |
| 4 | `AUD_CRE_DAT` | DATS | 8 | 🔑 | Completed Audit creation date |
| 5 | `AUD_CRE_TIM` | TIMS | 6 | 🔑 | Completed Audit creation time |
| 6 | `CHG_DAT` | DATS | 8 |  | Date changed |
| 7 | `CHG_TIM` | TIMS | 6 |  | Time changed |
| 8 | `STAUS` | CHAR | 2 |  | Audit status |
| 9 | `PRT_LET_DAT` | DATS | 8 |  | Print audit letter |
| 10 | `USR_LAST` | CHAR | 15 |  | Last assessed by |
| 11 | `CHG_DOM_DAT` | DATS | 8 |  | Change to domestic date |
| 12 | `CHG_REA` | CHAR | 1 |  | Change to domestic reason |
| 13 | `CHG_EFF_DAT` | DATS | 8 |  | Change to domestic effective date |
| 14 | `CHG_DOM_USR` | CHAR | 12 |  | Change to domestic userid |
| 15 | `CHG_ELD_DAT` | DATS | 8 |  | Change to elderly date |
| 16 | `CHG_ELD_EFF_DAT` | DATS | 8 |  | Change to elderly effective date |
| 17 | `CHG_ELD_USR` | CHAR | 12 |  | Change to elderly userid |
| 18 | `PRT_CAN_DAT` | DATS | 8 |  | Print cancel letter |
| 19 | `SECURITY` | CHAR | 12 |  | Security Deposit |
| 20 | `AUD_NEX_DAT` | DATS | 8 |  | Next audit date |
| 21 | `AUD_LAS_DAT` | DATS | 8 |  | Last audit date |
