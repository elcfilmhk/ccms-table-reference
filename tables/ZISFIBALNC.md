# ZISFIBALNC
**Description:** Table containing balance items
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_account_balance_get====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CONTRACT_ACCNT` | CHAR | 12 |  | Contract Account Number |
| 2 | `WITHD_VAL` | CHAR | 30 |  | Currency amount in BAPI interfaces |
| 3 | `CURRENCY` | CUKY | 5 |  | Currency Key |
| 4 | `CURRENCY_ISO` | CHAR | 3 |  | ISO Currency Code |
| 5 | `CCODE` | NUMC | 2 |  | MCRS Charge Code |
| 6 | `SCCODE` | NUMC | 2 |  | MCRS Sub Charge Code |
