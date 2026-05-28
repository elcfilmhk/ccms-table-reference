# ZISMDSPCERROR
**Description:** Error Report for Synchronization of Service Point Channel
**Total Fields:** 5
**Key Fields:** MANDT, ANLAGE, SERNR, ZWNUMMER

## Programs Using This Table
- `zismd0007`
- `zismd0008`
- `zismd0011`
- `zismd0030`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 5 | `MESSAGE` | CHAR | 80 |  | Error Message |
