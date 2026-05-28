# ZISFICALPAY
**Description:** Payment Files Readiness and Reconciliation Status
**Total Fields:** 5
**Key Fields:** MANDT, DATEREC, OFFIC_EX

## Programs Using This Table
- `zisfi0320`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DATEREC` | DATS | 8 | 🔑 | Date for File Receival and Reconciliation |
| 3 | `OFFIC_EX` | CHAR | 35 | 🔑 | External ID of Branch or Agent |
| 4 | `FILEREC` | CHAR | 1 |  | File Readiness Check |
| 5 | `RECON` | CHAR | 1 |  | Reconciliation Status |
