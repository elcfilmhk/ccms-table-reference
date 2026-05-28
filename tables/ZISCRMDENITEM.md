# ZISCRMDENITEM
**Description:** Data Enrichment -Survey-Question Item
**Total Fields:** 5
**Key Fields:** MANDT, ITEM_NO

## Programs Using This Table
- `ziscrm0006`
- `ziscrm0007`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ITEM_NO` | NUMC | 3 | 🔑 | Item Number |
| 3 | `ITEM` | CHAR | 35 |  | Item description (Data Enrichment) |
| 4 | `FORMAT_TYPE` | CHAR | 1 |  | Item Format Type - Dropdown / Freetext |
| 5 | `ACTIVE` | CHAR | 1 |  | Active Flag |
