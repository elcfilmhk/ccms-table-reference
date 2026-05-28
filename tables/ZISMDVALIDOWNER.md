# ZISMDVALIDOWNER
**Description:** Validation Owner for MDMS
**Total Fields:** 4
**Key Fields:** MANDT, METERTYPE

## Programs Using This Table
- `zismd0036`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `METERTYPE` | CHAR | 20 | 🔑 | Meter Type |
| 3 | `VALID_OWNER` | CHAR | 30 |  | Validation Owner |
| 4 | `PRIORITY` | INT1 | 3 |  | Priority |
