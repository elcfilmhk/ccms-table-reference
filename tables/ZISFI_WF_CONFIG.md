# ZISFI_WF_CONFIG
**Description:** Write Off Configuration
**Total Fields:** 6
**Key Fields:** MANDT, HVORG, TVORG

## Programs Using This Table
- `zisfi0287`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `CATEGORY` | CHAR | 20 |  | Category for Write Off |
| 5 | `FLAG` | CHAR | 1 |  | Exclude from Write Off |
| 6 | `REMARK` | CHAR | 100 |  | Remark |
