# ZISEDSMPDENDREG
**Description:** SMP Day-End Register Code mapping table
**Total Fields:** 3
**Key Fields:** MANDT, KENNZIFFFROM, KENNZIFFTO

## Programs Using This Table
- `zrmrd_fulfilment_day`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KENNZIFFFROM` | CHAR | 15 | 🔑 | Code for Identifying a Register |
| 3 | `KENNZIFFTO` | CHAR | 15 | 🔑 | Code for Identifying a Register |
