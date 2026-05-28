# ZISCEL_NEXT_HIST
**Description:** Concessionary audit transaction next audit date history
**Total Fields:** 7
**Key Fields:** MANDT, VKONT, HISTS

## Programs Using This Table
- `ziscs0443`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `HISTS` | DEC | 15 | 🔑 | Change timestamp |
| 4 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 5 | `BNDAT` | DATS | 8 |  | Before next audit date |
| 6 | `ANDAT` | DATS | 8 |  | After next audit date |
| 7 | `REMARK` | CHAR | 40 |  | Next audit date history remark |
