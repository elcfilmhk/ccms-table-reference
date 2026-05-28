# ZISCS_PON_OPTOUT
**Description:** List of Opt-Out CA
**Total Fields:** 3
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `ziscs_pon_ca_scr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `OPT_OUT_DATE` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
