# ZISCSSER_DTL
**Description:** eService Detail
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, TYPE, DETAIL

## Programs Using This Table
- `ziscs0004`
- `ziscs0333`
- `ziscs0338`
- `zisdm0278`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Type of eService |
| 4 | `DETAIL` | CHAR | 10 | 🔑 | Details of the eService type |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `STATUS` | CHAR | 1 |  | Status |
| 7 | `ERDAT` | CHAR | 14 |  | Creation Date |
| 8 | `ERNAM` | CHAR | 12 |  | Create By |
| 9 | `AEDAT` | CHAR | 14 |  | Change Date |
| 10 | `AENAM` | CHAR | 12 |  | Change By |
