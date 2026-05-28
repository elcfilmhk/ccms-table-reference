# ZISBIDEVPA
**Description:** Developer accounts
**Total Fields:** 6
**Key Fields:** MANDT, RB_YEAR, VKONT, TPLNR

## Programs Using This Table
- `zisbi0025`
- `zisbi0025_1`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RB_YEAR` | NUMC | 4 | 🔑 | Year for period |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `TPLNR` | CHAR | 30 | 🔑 | Functional Location |
| 5 | `STATUS` | CHAR | 40 |  | Description of functional location |
| 6 | `STAT_DATE` | DATS | 8 |  | Status date |
