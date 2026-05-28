# ZAEMFORM_DTL
**Description:** Detail table as the destination storage to save the AEM Form
**Total Fields:** 6
**Key Fields:** MANDT, FORM_TRAN_ID, FIELD_NAME, COUNTER

## Programs Using This Table
- `zcl_z_bapi_aemform_sav_mpc`
- `ziscs1121`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FORM_TRAN_ID` | CHAR | 12 | 🔑 | AEM form transaction ID |
| 3 | `FIELD_NAME` | CHAR | 50 | 🔑 | Component field name |
| 4 | `COUNTER` | NUMC | 5 | 🔑 | Counter |
| 5 | `VALUE` | CHAR | 255 |  | Component value |
| 6 | `TYPE` | CHAR | 20 |  | Component type |
