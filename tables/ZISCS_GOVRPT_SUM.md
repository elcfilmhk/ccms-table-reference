# ZISCS_GOVRPT_SUM
**Description:** Government entitlement report figure
**Total Fields:** 4
**Key Fields:** MANDT, RPTMTH, RPTKEY

## Programs Using This Table
- `ziscs0220`
- `ziscs0226`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`
- `ziscsgsrptreset`
- `zisfi0260`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPTMTH` | DATS | 8 | 🔑 | Government entitlement report month |
| 3 | `RPTKEY` | CHAR | 6 | 🔑 | Government entitlement report key |
| 4 | `RPTFIG` | CURR | 13 |  | Government entitlement report figure |
