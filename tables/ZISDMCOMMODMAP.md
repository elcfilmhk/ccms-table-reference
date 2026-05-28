# ZISDMCOMMODMAP
**Description:** Mapping of meter serial number with Communication Module ID
**Total Fields:** 3
**Key Fields:** MANDT, SERNR

## Programs Using This Table
- `zisdm0281`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `COMMODID` | CHAR | 30 |  | Communication Module ID |
