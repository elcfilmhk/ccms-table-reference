# ZISCS_ENTL_NOTES
**Description:** Reason for entitlement record
**Total Fields:** 5
**Key Fields:** MANDT, VKONT, CPUDT, CPUTM

## Programs Using This Table
- `ziscs0831`
- `ziscsgovsubmreverse`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 4 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 5 | `NOTES` | CHAR | 132 |  | Notes for entitlement |
