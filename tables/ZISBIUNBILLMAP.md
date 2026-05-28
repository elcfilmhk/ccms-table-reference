# ZISBIUNBILLMAP
**Description:** Unbilled reasons for departments
**Total Fields:** 3
**Key Fields:** MANDT, UNBILL_REAS

## Programs Using This Table
- `zisbi0042`
- `zisbi0042_1`
- `zisbi0042_2`
- `zisbi0042_ami`
- `zisbi0042_newfm`
- `zisbi0104`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `UNBILL_REAS` | CHAR | 50 | 🔑 | Unbilled Reason |
| 3 | `DEPARTMENT` | CHAR | 50 |  | Department |
