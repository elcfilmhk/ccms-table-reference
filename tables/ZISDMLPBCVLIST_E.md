# ZISDMLPBCVLIST_E
**Description:** Installations to be converted to load profile for Billing
**Total Fields:** 5
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
| 4 | `SERNR` | CHAR | 18 |  | Serial Number |
| 5 | `ERROR_MSG` | CHAR | 100 |  | Character 100 |
