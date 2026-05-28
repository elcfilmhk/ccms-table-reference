# ZISCS_EEC_BILL_CONS
**Description:** Billing Document with Contract Account
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0396_eec`
- `ziscseec_get_period_consump===ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `BILLDOCNO` | CHAR | 12 |  | Number of a billing document |
| 3 | `BILLSTART` | DATS | 8 |  | Start of billing period |
| 4 | `BILLEND` | DATS | 8 |  | End of billing period |
| 5 | `TTL_KWH` | DEC | 16 |  | Entry value (installed value) for a device |
