# ZISCSEBILL
**Description:** eBill Accounts Status
**Total Fields:** 20
**Key Fields:** MANDT, VKONT, CGDAT, CGTIM, RCTYP

## Programs Using This Table
- `ziscs0169`
- `ziscs0169_old`
- `ziscs0175`
- `ziscs0278`
- `zissd00076`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CGDAT` | DATS | 8 | 🔑 | Status Change Date |
| 4 | `CGTIM` | TIMS | 6 | 🔑 | Changed At |
| 5 | `RCTYP` | CHAR | 1 | 🔑 | Record Type |
| 6 | `CGUSR` | CHAR | 12 |  | Changed by |
| 7 | `GOVNT` | CHAR | 1 |  | Government Indicator |
| 8 | `DSPCT` | CHAR | 4 |  | Dispatch control for original customer |
| 9 | `CHENL` | CHAR | 20 |  | Channel |
| 10 | `TEAM` | CHAR | 40 |  | Team/Location |
| 11 | `ACCAT` | CHAR | 1 |  | Account Category |
| 12 | `RACAT` | CHAR | 10 |  | Rate category |
| 13 | `TRCLS` | CHAR | 4 |  | Account class |
| 14 | `SGLBL` | CHAR | 1 |  | Segment label |
| 15 | `OLD_DSPCT` | CHAR | 4 |  | Dispatch control for original customer |
| 16 | `NEW_DSPCT` | CHAR | 4 |  | Dispatch control for original customer |
| 17 | `SMSFAXIND` | CHAR | 1 |  | SMS/Fax billing indicator |
| 18 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 19 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 20 | `OPIND` | CHAR | 1 |  | eBill option in/out indicator |
