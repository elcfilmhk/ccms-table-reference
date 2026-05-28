# ZISDMVALROLOPUM
**Description:** Validation Group, Register Type and UM
**Total Fields:** 7
**Key Fields:** MANDT, DEV_REL_TYPE, REG_REL_TYPE, VAL_GRP, REG_TYPE

## Programs Using This Table
- `zisdm0147`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DEV_REL_TYPE` | CHAR | 25 | 🔑 | Device Relationship Type |
| 3 | `REG_REL_TYPE` | NUMC | 2 | 🔑 | Register relationship type |
| 4 | `VAL_GRP` | CHAR | 4 | 🔑 | Validation group for dependent validations |
| 5 | `REG_TYPE` | CHAR | 2 | 🔑 | Register type |
| 6 | `UM` | CHAR | 6 |  | Unit of measurement for meter reading |
| 7 | `RC` | NUMC | 2 |  | Register category |
