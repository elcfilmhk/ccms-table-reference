# ZISDM_REG_REL
**Description:** Customized Structure for FM Z_ISDM_METER_REMOVAL
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `z_isdm_meter_removal==========ft`
- `ziscs0015`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `INDEXNR` | NUMC | 12 |  | Consecutive number of register relationship |
| 2 | `ZWZUART` | NUMC | 2 |  | Register relationship type |
| 3 | `OPCODE` | NUMC | 2 |  | Operation code: Role of register in relationship |
| 4 | `PRUEFGR` | CHAR | 4 |  | Validation group for dependent validations |
