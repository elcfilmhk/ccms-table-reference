# ZCS_TXNNUM_LIST
**Description:** Structure for Get txnnum by BP ID or BP name
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_txnnum_by_bp=======ft`
- `zcl_z_bapi_get_txnnum__mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TXNNUM` | CHAR | 10 |  | CRM transaction no. |
| 2 | `IDNUMBER` | CHAR | 60 |  | Identification Number |
| 3 | `BPNAME` | CHAR | 50 |  | Description of a Business Partner |
| 4 | `STATUS` | CHAR | 1 |  | Status |
