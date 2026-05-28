# ZISCS_REC_CONFIG
**Description:** RE Cert Configuration Data
**Total Fields:** 10
**Key Fields:** MANDT, SERIAL_NO

## Programs Using This Table
- `zcl_z_iscseec_rec_conf_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERIAL_NO` | INT1 | 3 | 🔑 | Serial No |
| 3 | `RECERT_AVAILABILITY` | CHAR | 1 |  | RE Certificate Availability |
| 4 | `UNIT_PRICE` | DEC | 7 |  | Unit Price |
| 5 | `CURRENCY` | CUKY | 5 |  | Transaction Currency |
| 6 | `RT_MIN_UNIT` | INT4 | 10 |  | RT Minimum Unit |
| 7 | `RT_MAX_UNIT` | INT4 | 10 |  | RT Maximum Unit |
| 8 | `NRT_MIN_UNIT` | INT4 | 10 |  | NRT Minimum Unit |
| 9 | `NRT_MAX_UNIT` | INT4 | 10 |  | NRT Maximum Unit |
| 10 | `PURCHASE_MAX_MONTH` | INT4 | 10 |  | Purchase Maximum Month |
