# ZISDMBPINSTALL
**Description:** BP installation count table
**Total Fields:** 5
**Key Fields:** MANDT, GPART

## Programs Using This Table
- `zisdm0162`
- `zisdm0164`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `GST_COUNT` | NUMC | 6 |  | Count |
| 4 | `BULK_COUNT` | NUMC | 6 |  | Count |
| 5 | `LPT_COUNT` | NUMC | 6 |  | Count |
