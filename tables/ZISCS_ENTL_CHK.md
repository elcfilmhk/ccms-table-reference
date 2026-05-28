# ZISCS_ENTL_CHK
**Description:** Gov subsidy healh check
**Total Fields:** 28
**Key Fields:** MANDT, VERSION, VKONT, VERTRAG, ANLAGE

## Programs Using This Table
- `ziscs0342`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERSION` | NUMC | 3 | 🔑 | Version Number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 5 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 6 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 7 | `VSTELLE` | CHAR | 10 |  | Premise |
| 8 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 9 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 10 | `ERDAT` | DATS | 8 |  | Move-in Doc. Create on |
| 11 | `AEDAT` | DATS | 8 |  | Move in Doc Changed on |
| 12 | `FR_DEVP` | CHAR | 1 |  | From Developer |
| 13 | `EXPECT_ENTL` | CURR | 13 |  | Expected Entitlement Grant |
| 14 | `ACTUAL_ENTL` | CURR | 13 |  | Actual Entitlement Grant |
| 15 | `NOTMATCH` | CHAR | 1 |  | Not match |
| 16 | `PROCID` | CHAR | 12 |  | Process ID |
| 17 | `ENT_AFTER` | CHAR | 1 |  | Entitlement after Move Out |
| 18 | `HAUS` | CHAR | 30 |  | Connection Object |
| 19 | `STAT` | CHAR | 5 |  | Object status |
| 20 | `TDLINE` | CHAR | 132 |  | Text Line |
| 21 | `TDGPART` | CHAR | 10 |  | Business Partner Number |
| 22 | `PRE_VERTRAG` | CHAR | 10 |  | Contract |
| 23 | `PRE_VKONT` | CHAR | 12 |  | Contract Account Number |
| 24 | `PRE_BP` | CHAR | 10 |  | Business Partner Number |
| 25 | `CPUDT` | DATS | 8 |  | Day On Which Accounting Document Was Entered |
| 26 | `CPUTM` | TIMS | 6 |  | Time of Entry |
| 27 | `REFMTH_FR` | DATS | 8 |  | Entitlement ref month from |
| 28 | `REFMTH_TO` | DATS | 8 |  | Entitlement ref month to |
