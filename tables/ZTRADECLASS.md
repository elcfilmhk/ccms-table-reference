# ZTRADECLASS
**Description:** Trade class for GST customer
**Total Fields:** 4
**Key Fields:** MANDT, SPRAS, KTOKL

## Programs Using This Table
- `z_bapi_get_trade_class========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SPRAS` | LANG | 1 | 🔑 | Language Key |
| 3 | `KTOKL` | CHAR | 4 | 🔑 | Account class |
| 4 | `KTOTX` | CHAR | 100 |  | Trade Class Description |
