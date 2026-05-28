# ZISBIECOACCLST
**Description:** ECO alert account list table
**Total Fields:** 5
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbi0159`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `AB` | DATS | 8 |  | Vaid from date |
| 4 | `BIS` | DATS | 8 |  | Vaid to date |
| 5 | `REMARK` | CHAR | 100 |  | Remark of ECO alert account |
