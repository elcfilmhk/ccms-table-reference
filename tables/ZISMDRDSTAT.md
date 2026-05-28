# ZISMDRDSTAT
**Description:** Mapping on Reading Status of Meter Reading Status
**Total Fields:** 4
**Key Fields:** MANDT, ABLSTAT, ISTABLART

## Programs Using This Table
- `zismd0009`
- `zismd0012`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLSTAT` | CHAR | 1 | 🔑 | Meter Reading Status |
| 3 | `ISTABLART` | CHAR | 2 | 🔑 | Meter reading type |
| 4 | `STATUS` | CHAR | 30 |  | Meter Reading Status |
