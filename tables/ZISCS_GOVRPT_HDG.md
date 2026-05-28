# ZISCS_GOVRPT_HDG
**Description:** Government entitlement report heading
**Total Fields:** 4
**Key Fields:** MANDT, RPTKEY

## Programs Using This Table
- `ziscs0226`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPTKEY` | CHAR | 6 | 🔑 | Government entitlement report key |
| 3 | `RPTHDG` | CHAR | 80 |  | Government entitlement report heading |
| 4 | `RPTDSC` | CHAR | 20 |  | Government entitlement report short description |
