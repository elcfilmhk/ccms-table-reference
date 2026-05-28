# ZISFI_CREDDEB
**Description:** Unique transactionID to prevent record from regeneration
**Total Fields:** 2
**Key Fields:** MANDT, TRANSID

## Programs Using This Table
- `zisfi0066`
- `zrfkkpcds`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRANSID` | CHAR | 42 | 🔑 | Trasanction ID for preventing regeneration of file in CreDeB |
