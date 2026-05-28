# ZISDMMTRRITYPE
**Description:** Meter remote interrogation type
**Total Fields:** 3
**Key Fields:** MANDT, SERNR

## Programs Using This Table
- `zisdm0341`
- `zisdm0343`
- `zised0049`
- `zismd0035`
- `zismd0035_nov17`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `RITYPE` | CHAR | 1 |  | RI Type |
