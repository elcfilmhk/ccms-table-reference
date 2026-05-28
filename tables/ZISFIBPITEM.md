# ZISFIBPITEM
**Description:** Posting Request BP item
**Total Fields:** 11
**Key Fields:** MANDT, ZZREBATE_REF

## Programs Using This Table
- `zisfi0138`
- `zisfi0197`
- `zisfi0197_smis`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZREBATE_REF` | CHAR | 16 | 🔑 | Rebate reference |
| 3 | `BLART` | CHAR | 2 |  | Document Type |
| 4 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 5 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 6 | `SPART` | CHAR | 2 |  | Division |
| 7 | `LOCKR_P` | CHAR | 1 |  | Lock reason (Payment) |
| 8 | `LOCKR_D` | CHAR | 1 |  | Lock reason (Dunning) |
| 9 | `VERKZ` | CHAR | 1 |  | Item Can Only Be Cleared |
| 10 | `ZZIGNORE_FINAL` | CHAR | 1 |  | Flag - Ignore final invoiced account |
| 11 | `HERKF` | CHAR | 2 |  | Document Origin Key |
