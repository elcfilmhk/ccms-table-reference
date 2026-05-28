# ZISBIBBMAP
**Description:** Budget billing item mapping table
**Total Fields:** 4
**Key Fields:** MANDT, HVORG, TVORG

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `LINE_ITEM` | CHAR | 6 |  | Line Item |
