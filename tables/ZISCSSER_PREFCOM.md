# ZISCSSER_PREFCOM
**Description:** Preferred Communication Channel
**Total Fields:** 9
**Key Fields:** MANDT, VKONT, TYPE, DISPATCH

## Programs Using This Table
- `ziscs0484`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Type of eService |
| 4 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 5 | `PREFERENCE` | CHAR | 1 |  | Preference |
| 6 | `ERDAT` | CHAR | 14 |  | Creation Date |
| 7 | `ERNAM` | CHAR | 12 |  | Create By |
| 8 | `AEDAT` | CHAR | 14 |  | Change Date |
| 9 | `AENAM` | CHAR | 12 |  | Change By |
