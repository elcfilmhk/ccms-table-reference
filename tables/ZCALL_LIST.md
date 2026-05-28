# ZCALL_LIST
**Description:** Call List return for RFC
**Total Fields:** 3
**Key Fields:** _none_

## Programs Using This Table
- `zisfi0005_dun`
- `zisfi0214`
- `zisfi0215`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 3 | `STATUS` | CHAR | 1 |  | Payment reminder call status (S=Success, F=not Success) |
