# ZISHOTLINELOC
**Description:** Residential Bonus Scheme Hotline Location
**Total Fields:** 11
**Key Fields:** MANDT, LOCATION

## Programs Using This Table
- `ziscs0237`
- `zissd00086a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOCATION` | CHAR | 30 | 🔑 | Hot line location |
| 3 | `BRANCH` | CHAR | 30 |  | Branch |
| 4 | `PRIORITY` | NUMC | 2 |  | Display Priority |
| 5 | `VKBUR` | CHAR | 4 |  | Sales Office |
| 6 | `BEZEI` | CHAR | 20 |  | Description |
| 7 | `PREAPPLOC` | CHAR | 1 |  | Pre-approval Location |
| 8 | `APPLOC` | CHAR | 1 |  | Approval Location |
| 9 | `CUST_REFBR` | CHAR | 1 |  | Customer reference branch |
| 10 | `WIS` | CHAR | 1 |  | Wiring Inspection Service |
| 11 | `CUST_REFCSC` | CHAR | 1 |  | List Customer Reference data for CSC |
