# ZCONT_ACC
**Description:** Table to store account id and ownership id
**Total Fields:** 5
**Key Fields:** CLIENT, CONTRACTACCOUNT, PARTNER

## Programs Using This Table
- `z_ownership_conv_parallel_job`
- `z_ownership_conversion`
- `ziscrm0005`
- `ziscrm0017`
- `ziscrm0017a`
- `ziscrm0018`
- `ziscrm0018a`
- `ziscrm_upd_zcont_acc`
- `ziscrm_update_ca_ownership`
- `ziscs0151`
- `ziscs0467`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `CONTRACTACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `PARTNER` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `BNAME` | CHAR | 12 |  | User Name in User Master Record |
| 5 | `CA_OWNER` | CHAR | 4 |  | BP ownership |
