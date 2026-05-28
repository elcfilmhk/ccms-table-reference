# ZISBI_BILLPERIOD_VALID_IN
**Description:** Installtion to be verified for Rebill/reverse scenario
**Total Fields:** 4
**Key Fields:** _none_

## Programs Using This Table
- `zisbi0042`
- `zisbi0042_1`
- `zisbi0042_2`
- `zisbi0042_newfm`
- `zisbi0262`
- `zisbi0263`
- `zreaexcep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `SCH_BILLINGDATE` | DATS | 8 |  | Scheduled Billing Date |
| 4 | `BACKDATE_14` | DATS | 8 |  | Scheduled Billing Date |
