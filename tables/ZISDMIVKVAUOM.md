# ZISDMIVKVAUOM
**Description:** Check setting on independent validation
**Total Fields:** 5
**Key Fields:** MANDT, PRUEFPKT

## Programs Using This Table
- `zisdm0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRUEFPKT` | CHAR | 2 | 🔑 | Independent validations (customer-specific) |
| 3 | `ON_KVA_CHECK` | CHAR | 1 |  | X V check for on-peak kVA |
| 4 | `SEMI_KVA_CHECK` | CHAR | 1 |  | X V check for semi-peak KVA |
| 5 | `OFF_KVA_CHECK` | CHAR | 1 |  | X V check for off-peak KVA |
