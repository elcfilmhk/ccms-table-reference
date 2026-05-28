# ZISDMGPBCHKREAD
**Description:** The group bill reading
**Total Fields:** 11
**Key Fields:** MANDT, RUNDATE, ABLBELNR

## Programs Using This Table
- `z_isdm_create_grpbill_chkread=ft`
- `zisdm0050`
- `zisdm0254`
- `zisdm0408`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Run Date |
| 3 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
| 4 | `SERNR` | CHAR | 18 |  | Serial Number |
| 5 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `ABLESGR` | CHAR | 2 |  | Meter reading reason |
| 8 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 9 | `ISTABLART` | CHAR | 2 |  | Meter reading type |
| 10 | `V_ZWSTAND` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 11 | `ZWNUMMER` | NUMC | 3 |  | Register |
