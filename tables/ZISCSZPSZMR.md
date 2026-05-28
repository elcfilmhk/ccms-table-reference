# ZISCSZPSZMR
**Description:** Relationship for ZPS/P09 order auto gen ZMR/R10 order table
**Total Fields:** 3
**Key Fields:** MANDT, ZPS_ORDER

## Programs Using This Table
- `ziscs0005`
- `ziscsriaufk20`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZPS_ORDER` | CHAR | 12 | 🔑 | Order Number |
| 3 | `ZMR_ORDER` | CHAR | 12 |  | Order Number |
