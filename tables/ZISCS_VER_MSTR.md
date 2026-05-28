# ZISCS_VER_MSTR
**Description:** Government Subsidy Migration Version Table
**Total Fields:** 4
**Key Fields:** CLIENT, VERSION, ENTRY_DATE

## Programs Using This Table
- `ziscs0860`
- `ziscs0860_new`
- `ziscs0861`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERSION` | NUMC | 2 | 🔑 | Version |
| 3 | `ENTRY_DATE` | DATS | 8 | 🔑 | Creation date |
| 4 | `TEXT` | CHAR | 100 |  | Version text |
