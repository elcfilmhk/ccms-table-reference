# ZISDMAPRLIMIT
**Description:** Consumption limit
**Total Fields:** 5
**Key Fields:** MANDT, BRANCH, POST, MASSREAD

## Programs Using This Table
- `zisdm0181`
- `zisdm0182`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BRANCH` | CHAR | 40 | 🔑 | Branch |
| 3 | `POST` | NUMC | 8 | 🔑 | Object ID |
| 4 | `MASSREAD` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 5 | `CONSUM` | DEC | 13 |  | Consumption limit |
