# ZISBIBONCNT
**Description:** Contract account email bounce count
**Total Fields:** 4
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbi0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `BCOUNT` | NUMC | 8 |  | Email bounce count |
| 4 | `LCHGDATE` | DATS | 8 |  | Last Changed On |
