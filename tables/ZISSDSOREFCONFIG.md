# ZISSDSOREFCONFIG
**Description:** Sales Order Reference for Retail Sales (Config. Table)
**Total Fields:** 4
**Key Fields:** MANDT, FIELD, VLKEY

## Programs Using This Table
- `zissd00085`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FIELD` | CHAR | 10 | 🔑 | List Box Field Name |
| 3 | `VLKEY` | CHAR | 4 | 🔑 | Value Key |
| 4 | `VLDES` | CHAR | 40 |  | Value Description |
