# ZISCEL_AUDIT_MAS
**Description:** Concessionary audit master
**Total Fields:** 9
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `ziscs0400`
- `ziscs0405`
- `ziscs0406`
- `ziscs0410`
- `ziscs0420`
- `ziscs0440`
- `ziscs0442`
- `ziscs0443`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ADC` | DEC | 8 |  | ADC |
| 4 | `ADC_CHG_DAT` | DATS | 8 |  | ADC update date |
| 5 | `AUD_CRE_DAT` | DATS | 8 |  | Completed Audit creation date |
| 6 | `AUD_CRE_TIM` | TIMS | 6 |  | Completed Audit creation time |
| 7 | `AUD_NEX_DAT` | DATS | 8 |  | Next audit date |
| 8 | `AUD_LAS_DAT` | DATS | 8 |  | Last audit date |
| 9 | `USR_LAST` | CHAR | 15 |  | Last assessed by |
