# ZISBIRBCONFIG
**Description:** Random Bill Selection Report Configuration
**Total Fields:** 5
**Key Fields:** MANDT, RPT, ZINDEX, TARIFTYP

## Programs Using This Table
- `zisbi0020`
- `zisbi0270`
- `zisbi0270t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RPT` | CHAR | 4 | 🔑 | Report |
| 3 | `ZINDEX` | NUMC | 4 | 🔑 | Index |
| 4 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 5 | `CRITERIA` | CHAR | 30 |  | Criteria |
