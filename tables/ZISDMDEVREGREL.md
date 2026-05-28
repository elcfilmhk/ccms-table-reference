# ZISDMDEVREGREL
**Description:** Device Register Relationship
**Total Fields:** 5
**Key Fields:** MANDT, DEV_REL_TYPE, MTR_ROLE, OP_CODE

## Programs Using This Table
- `zisdm0147`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DEV_REL_TYPE` | CHAR | 25 | 🔑 | Device Relationship Type |
| 3 | `MTR_ROLE` | CHAR | 20 | 🔑 | Meter Role |
| 4 | `OP_CODE` | NUMC | 2 | 🔑 | Operation code: Role of register in relationship |
| 5 | `MULTIPLE` | CHAR | 1 |  | Multiple |
