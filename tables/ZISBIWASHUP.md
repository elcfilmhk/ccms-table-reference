# ZISBIWASHUP
**Description:** Budget billing data comparison
**Total Fields:** 6
**Key Fields:** MANDT, PAYMENT_PLAN, BILL_MONTH

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PAYMENT_PLAN` | CHAR | 12 | 🔑 | Budget billing plan |
| 3 | `BILL_MONTH` | CHAR | 6 | 🔑 | Bill Month |
| 4 | `PLAN_CHARGE` | CURR | 13 |  | BB Plan charge |
| 5 | `ACTUAL_CONSUMP` | DEC | 17 |  | Actual consumption |
| 6 | `STD_CHARGE` | CURR | 13 |  | Standard charge |
