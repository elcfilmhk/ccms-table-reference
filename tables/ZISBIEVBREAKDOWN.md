# ZISBIEVBREAKDOWN
**Description:** TOU EV-NEBE Posting Breakdown
**Total Fields:** 8
**Key Fields:** MANDT, NEBE_FICA_DOC, CHARGE_TYPE

## Programs Using This Table
- `zisbi0271`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `NEBE_FICA_DOC` | CHAR | 12 | 🔑 | NEBE FICA Doc |
| 3 | `CHARGE_TYPE` | CHAR | 4 | 🔑 | Charge Type |
| 4 | `CSMP` | DEC | 31 |  | Energy Consumption |
| 5 | `CHRG` | CURR | 13 |  | Charge Amount for Charge Type |
| 6 | `BILLING_FROM` | DATS | 8 |  | Start of billing period |
| 7 | `BILLING_TO` | DATS | 8 |  | End of billing period |
| 8 | `VKONT` | CHAR | 12 |  | Contract Account Number |
