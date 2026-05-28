# ZISCSEEC_TXTTAGS
**Description:** Text-Tag relationship
**Total Fields:** 7
**Key Fields:** MANDT, TAG, TXT_ID

## Programs Using This Table
- `zcl_ziscseec_ep_trans__mpc`
- `ziscs0380_eec`
- `ziscs0471_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TAG` | CHAR | 80 | 🔑 | Tag for Texts |
| 3 | `TXT_ID` | CHAR | 100 | 🔑 | Text ID |
| 4 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 6 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
