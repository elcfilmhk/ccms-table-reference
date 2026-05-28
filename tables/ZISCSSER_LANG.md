# ZISCSSER_LANG
**Description:**  Preferred Language for eService
**Total Fields:** 8
**Key Fields:** MANDT, VKONT, TYPE

## Programs Using This Table
- `ziscs0484`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Type of eService |
| 4 | `LANG` | LANG | 1 |  | Language Key |
| 5 | `ERDAT` | CHAR | 14 |  | Creation Date |
| 6 | `ERNAM` | CHAR | 12 |  | Create By |
| 7 | `AEDAT` | CHAR | 14 |  | Change Date |
| 8 | `AENAM` | CHAR | 12 |  | Change By |
