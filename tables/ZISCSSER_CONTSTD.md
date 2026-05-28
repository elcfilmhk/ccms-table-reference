# ZISCSSER_CONTSTD
**Description:** Eservice Contact Standard
**Total Fields:** 4
**Key Fields:** MANDT, VKONT, DISPATCH

## Programs Using This Table
- `ziscs0346`
- `ziscs0347`
- `ziscs0348`
- `ziscs0484`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 4 | `ITEM` | CHAR | 10 |  | Item Number for Contact Number |
