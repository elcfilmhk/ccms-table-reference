# ZFIGLBAMAP
**Description:** Mapping table between GL account and Business Area
**Total Fields:** 5
**Key Fields:** MANDT, BUKRS, KTOPL, HKONT

## Programs Using This Table
- `zggbs000`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BUKRS` | CHAR | 4 | 🔑 | Company Code |
| 3 | `KTOPL` | CHAR | 4 | 🔑 | Chart of Accounts |
| 4 | `HKONT` | CHAR | 10 | 🔑 | General Ledger Account |
| 5 | `GSBER` | CHAR | 4 |  | Business Area |
