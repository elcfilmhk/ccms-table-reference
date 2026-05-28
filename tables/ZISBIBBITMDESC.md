# ZISBIBBITMDESC
**Description:** Line item description table
**Total Fields:** 6
**Key Fields:** MANDT, CAT_TYPE, LINE_ITEM, SORTKEY

## Programs Using This Table
- `zisbi0108`
- `zisbi0112`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CAT_TYPE` | CHAR | 2 | 🔑 | Category |
| 3 | `LINE_ITEM` | CHAR | 6 | 🔑 | Line Item |
| 4 | `SORTKEY` | NUMC | 4 | 🔑 | Sorting Sequence |
| 5 | `EN_DESC` | CHAR | 80 |  | English Description |
| 6 | `CHN_DESC` | CHAR | 80 |  | Chinese Description |
