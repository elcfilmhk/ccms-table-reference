# ZISCSINCCHARGE
**Description:** Incentive Charge
**Total Fields:** 5
**Key Fields:** MANDT, PROMO, EFF_FROM

## Programs Using This Table
- `ziscs0210`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMO` | CHAR | 20 | 🔑 | Promotion name |
| 3 | `EFF_FROM` | DATS | 8 | 🔑 | Effective From Date |
| 4 | `EFF_END` | DATS | 8 |  | Effective End Date |
| 5 | `CHARGE` | CURR | 13 |  | Amount to be charged |
