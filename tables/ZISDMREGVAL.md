# ZISDMREGVAL
**Description:** Relationship Type and Validation Group
**Total Fields:** 4
**Key Fields:** MANDT, DEV_REL_TYPE, REG_REL_TYPE, VAL_GRP

## Programs Using This Table
- `zisdm0147`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DEV_REL_TYPE` | CHAR | 25 | 🔑 | Device Relationship Type |
| 3 | `REG_REL_TYPE` | NUMC | 2 | 🔑 | Register relationship type |
| 4 | `VAL_GRP` | CHAR | 4 | 🔑 | Validation group for dependent validations |
