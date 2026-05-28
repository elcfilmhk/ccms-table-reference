# ZISCS_G2011_NOTE
**Description:** Government entitlement note 2011/2012
**Total Fields:** 4
**Key Fields:** MANDT, NOTE_NO

## Programs Using This Table
- `ziscs0226`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NOTE_NO` | NUMC | 2 | 🔑 | Government entitlement note number |
| 3 | `NOTE_HEAD` | CHAR | 99 |  | Government entitlement note heading |
| 4 | `NOTE_DETAIL` | CHAR | 255 |  | Government entitlement note detail |
