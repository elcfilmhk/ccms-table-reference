# ZISFISPECPROC
**Description:** Specify business process
**Total Fields:** 7
**Key Fields:** MANDT, HVORG, TVORG

## Programs Using This Table
- `zisfi0105`
- `zisfi0207`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `REFD_ACSTATUS` | CHAR | 1 |  | Refund process - trigger for account status |
| 5 | `REFUND` | CHAR | 1 |  | Refund indicator: X = active, space = inactive |
| 6 | `TRANSF_POST` | CHAR | 1 |  | Transfer posting indicator: X = active, space = inactive |
| 7 | `WRITE_OFF` | CHAR | 1 |  | (obsolete)Write-Off/In indic: X = active, space = inactive |
