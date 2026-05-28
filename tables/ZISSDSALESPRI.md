# ZISSDSALESPRI
**Description:** Division determination rules
**Total Fields:** 8
**Key Fields:** MANDT, OBJ_NAME, VKBUR, SPART, VKGRP, VTWEG

## Programs Using This Table
- `zsd_get_generic_refkey========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJ_NAME` | CHAR | 40 | 🔑 | Object Name in Object Directory |
| 3 | `VKBUR` | CHAR | 4 | 🔑 | Sales Office |
| 4 | `SPART` | CHAR | 2 | 🔑 | Division |
| 5 | `VKGRP` | CHAR | 3 | 🔑 | Sales Group |
| 6 | `VTWEG` | CHAR | 2 | 🔑 | Distribution Channel |
| 7 | `PRIORITY` | NUMC | 4 |  | Priority |
| 8 | `REFKEY` | CHAR | 30 |  | Reference Key |
