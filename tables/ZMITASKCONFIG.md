# ZMITASKCONFIG
**Description:** Custom table to configure Move-in/Move-out task assignment
**Total Fields:** 4
**Key Fields:** MANDT, TYPE, CHANNEL

## Programs Using This Table
- `ziscs0261`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 2 | 🔑 | Task Type |
| 3 | `CHANNEL` | CHAR | 2 | 🔑 | Move-In/Move Out Channel |
| 4 | `MAX_WORK` | NUMC | 3 |  | Max. daily workload |
