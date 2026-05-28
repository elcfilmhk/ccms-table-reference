# ZISDMPCONS
**Description:** Customized table for periodic consumption
**Total Fields:** 8
**Key Fields:** MANDT, ZZMETERSIZE

## Programs Using This Table
- `zisdm0022_bulk`
- `zisdm0034`
- `zisdm0052`
- `zisdm0072`
- `zisdmupld`
- `zised0013`
- `zismd0008`
- `zismd0011`
- `zismd0023`
- `zismd0030`
- `zismd0034`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZMETERSIZE` | CHAR | 18 | 🔑 | Size/dimension |
| 3 | `ZZPRCONS_KWH` | CHAR | 14 |  | KWH Periodic Consumption |
| 4 | `ZZPRCONS_KVA` | CHAR | 14 |  | KVA Periodic Consumption |
| 5 | `ZZPRCONS_KVAH` | CHAR | 14 |  | KVAH Periodic Consumption |
| 6 | `ZZPRCONS_KVARH` | CHAR | 14 |  | KVARH Periodic Consumption |
| 7 | `ZZDAYS` | NUMC | 3 |  | Number of days |
| 8 | `ZZCURRENT` | NUMC | 8 |  | Current |
