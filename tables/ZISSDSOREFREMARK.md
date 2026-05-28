# ZISSDSOREFREMARK
**Description:** Sales Order Reference Remark
**Total Fields:** 5
**Key Fields:** MANDT, SALES_ORDER_REF, ITEM_NO

## Programs Using This Table
- `zissd00086`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_ORDER_REF` | CHAR | 18 | 🔑 | Sales Order Reference Number |
| 3 | `ITEM_NO` | NUMC | 6 | 🔑 | Item Number |
| 4 | `REMARK` | CHAR | 200 |  | Remark |
| 5 | `ADDITION_REMARK` | CHAR | 100 |  | Additional Remark |
