# ZISDMADRCONFIG
**Description:** ADR Configuration table
**Total Fields:** 7
**Key Fields:** MANDT, ITEMNAME, ITEMSEQ

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0313_adr`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ITEMNAME` | CHAR | 30 | 🔑 | ADR Configuration Item Name |
| 3 | `ITEMSEQ` | NUMC | 4 | 🔑 | ADR Item Sequence Number |
| 4 | `SIGN` | CHAR | 1 |  | Type of SIGN component in row type of a Ranges type |
| 5 | `OPTN` | CHAR | 2 |  | Type of OPTION component in row type of a Ranges type |
| 6 | `LOW` | CHAR | 50 |  | ADR Range low value |
| 7 | `HIGH` | CHAR | 50 |  | ADR Range high value |
