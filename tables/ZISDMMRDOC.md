# ZISDMMRDOC
**Description:** Table to store MRDoc temporarily for reporting purposes
**Total Fields:** 2
**Key Fields:** MANDT, ABLBELNR

## Programs Using This Table
- `zisdm0040`
- `zisdm0050`
- `zmrdoc`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLBELNR` | CHAR | 20 | 🔑 | Internal ID for meter reading document |
