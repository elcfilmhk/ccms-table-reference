# ZISSDCUSTREMOVAL
**Description:** Retail Sales Order Customer data removal
**Total Fields:** 9
**Key Fields:** MANDT, SALES_ORDER

## Programs Using This Table
- `ziscrm0049`
- `zissd00111`
- `zissd00113`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER` | CHAR | 10 | 🔑 | Sales Document |
| 3 | `STATUS` | CHAR | 1 |  | Retail Sales Order Status: Completed / Cancelled |
| 4 | `ISU` | CHAR | 1 |  | Indicator: Retail Sales Order only exist in ISU system |
| 5 | `SALES_ORDER_REF` | CHAR | 1 |  | Indicator: Sales Customer Reference found? |
| 6 | `PO_MASK_IND` | CHAR | 1 |  | Indicator: Purchase Order Finished Masking? |
| 7 | `CHANGED_DATE` | DATS | 8 |  | Retail Sales Order customer contact data masked date |
| 8 | `CHANGED_TIME` | TIMS | 6 |  | Retail Sales Order customer contact data masked time |
| 9 | `CHANGED_BY` | CHAR | 12 |  | Retail Sales Order customer contact data masked by |
