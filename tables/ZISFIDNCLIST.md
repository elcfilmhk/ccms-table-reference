# ZISFIDNCLIST
**Description:** Dunning due call list
**Total Fields:** 3
**Key Fields:** MANDT, DUE_DATE, VKONT

## Programs Using This Table
- `zisfi0214`
- `zisfi0215`
- `zisfi0273`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DUE_DATE` | DATS | 8 | 🔑 | Dunning due date |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
