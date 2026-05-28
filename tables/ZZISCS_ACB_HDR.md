# ZZISCS_ACB_HDR
**Description:** Info. pertaining to the ACB SMS service as a whole
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_acb_get_ca_sms==============ft`
- `ziscs0407`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | Info. pertaining to the ACB SMS service as a whole |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `ACTIVE_FLAG` | CHAR | 1 |  | Single-Character Flag |
| 5 | `LAST_CHANGE_DT` | CHAR | 14 |  | Changed Datetime |
| 6 | `LAST_CHANGE_USER` | CHAR | 12 |  | Changed By |
