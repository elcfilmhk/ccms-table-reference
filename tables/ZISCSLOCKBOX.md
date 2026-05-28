# ZISCSLOCKBOX
**Description:** Lockbox Registration
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `zisbi0127`
- `ziscs0331`
- `ziscs0336`
- `ziscs0348`
- `ziscs0350`
- `ziscs0352`
- `zisfi0224`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `RECEIPT` | CHAR | 1 |  | LockBox Receipt delivery method |
| 5 | `SMS` | CHAR | 8 |  | Lockbox receipt SMS No. |
| 6 | `EMAIL` | CHAR | 100 |  | Lockbox receipt Email address |
