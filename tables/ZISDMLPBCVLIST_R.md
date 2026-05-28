# ZISDMLPBCVLIST_R
**Description:** Installations to be converted to load profile for Billing
**Total Fields:** 10
**Key Fields:** MANDT, ANLAGE, ADATSOLL

## Programs Using This Table
- `zisdm0201_main`
- `zisdm0201_sub_gp`
- `zisdm0201_sub_lp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 4 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `ORG_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 8 | `REV_RDG` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 9 | `ORG_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
| 10 | `REV_CONSUMPTION` | DEC | 17 |  | Places Before Decimal Point in Meter Reading |
