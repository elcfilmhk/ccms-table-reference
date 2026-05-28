# ZCRM_SALESORDER_MASK
**Description:** Retail Sales Order customer data mask
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `ziscrm0049`
- `zissd00111`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VBELN` | CHAR | 10 |  | Sales Document |
| 2 | `STATUS` | CHAR | 1 |  | Retail Sales Order Status: Completed / Cancelled |
| 3 | `CHANGE_AT` | DATS | 8 |  | Status change date |
