# ZISCS_PROCESS_ID
**Description:** Entitlement process ID
**Total Fields:** 5
**Key Fields:** MANDT, PROCID

## Programs Using This Table
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROCID` | CHAR | 12 | 🔑 | Process ID |
| 3 | `SDESCR` | CHAR | 25 |  | Short description for entitlement process ID |
| 4 | `DESCR` | CHAR | 40 |  | Description for entitlement process ID |
| 5 | `PROCGP` | CHAR | 12 |  | Process group |
