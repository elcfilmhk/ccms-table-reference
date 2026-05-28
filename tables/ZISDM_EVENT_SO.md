# ZISDM_EVENT_SO
**Description:** SMP Event Type Order Mapping
**Total Fields:** 4
**Key Fields:** MANDT, EVENTTYPECODE

## Programs Using This Table
- `zcl_ami_fdt_utility`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `EVENTTYPECODE` | NUMC | 4 | 🔑 | Event Type Code |
| 3 | `AUART` | CHAR | 4 |  | Order Type |
| 4 | `ILART` | CHAR | 3 |  | Maintenance activity type |
