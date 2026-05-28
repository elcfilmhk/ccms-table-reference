# ZISFINEBEGLMAP
**Description:** NEBE GL maping check table
**Total Fields:** 4
**Key Fields:** MANDT, HVORG, TVORG, ZZSEQNO

## Programs Using This Table
- `z_fi_bapi_nebe_upload=========ft`
- `zisdm0369_ssr`
- `zisdm0369_ssr_mod`
- `zisfi0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `HVORG` | CHAR | 4 | 🔑 | Main Transaction for Line Item |
| 3 | `TVORG` | CHAR | 4 | 🔑 | Subtransaction for Document Item |
| 4 | `ZZSEQNO` | NUMC | 4 | 🔑 | Sequence Num. |
