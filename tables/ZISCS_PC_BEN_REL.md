# ZISCS_PC_BEN_REL
**Description:** Value table for the relationship details
**Total Fields:** 3
**Key Fields:** MANDT, REL_CODE

## Programs Using This Table
- `ziscs0800`
- `ziscs0805`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REL_CODE` | CHAR | 2 | 🔑 | Relationship Code |
| 3 | `RELATION` | CHAR | 20 |  | Relationship description |
