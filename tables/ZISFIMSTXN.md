# ZISFIMSTXN
**Description:** Table for Main/Sub Transactions
**Total Fields:** 4
**Key Fields:** MANDT, ZZTYPE, HVORG, TVORG

## Programs Using This Table
- `zisfi0141_bkgrd`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZTYPE` | CHAR | 3 | 🔑 | Type of enhancement |
| 3 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 4 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
