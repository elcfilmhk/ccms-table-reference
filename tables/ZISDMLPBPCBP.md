# ZISDMLPBPCBP
**Description:** Load profile billing proactive communication BP check
**Total Fields:** 6
**Key Fields:** MANDT, GPART, VKONT, BNAME

## Programs Using This Table
- `ziscs0031`
- `zisdm0022`
- `zisdm0200`
- `zisdm0239`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `BNAME` | CHAR | 12 | 🔑 | User Name in User Master Record |
| 5 | `PCDATE` | DATS | 8 |  | Proactive Communication Date |
| 6 | `MESSAGE` | CHAR | 50 |  | Special Message |
