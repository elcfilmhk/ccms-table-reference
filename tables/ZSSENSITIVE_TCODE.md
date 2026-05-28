# ZSSENSITIVE_TCODE
**Description:** Return for ZFI_GET_SENSITIVE_TCODE
**Total Fields:** 7
**Key Fields:** _none_

## Programs Using This Table
- `zcl_z_test11111_mpc`
- `zcl_zfi_get_sensitive__mpc`
- `zfi_get_sensitive_tcode=======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 |  | Client |
| 2 | `SYS` | CHAR | 10 |  | System |
| 3 | `TCODE` | CHAR | 20 |  | Transaction Code |
| 4 | `AGR_NAME` | CHAR | 30 |  | Composite role |
| 5 | `TCODE_TEXT` | CHAR | 36 |  | Transaction text |
| 6 | `TXN_INDICATOR` | CHAR | 5 |  | Transaction Indicator |
| 7 | `REMARK` | CHAR | 100 |  | Remark |
