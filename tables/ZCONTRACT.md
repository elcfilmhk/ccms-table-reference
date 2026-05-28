# ZCONTRACT
**Description:** Contract with anlage for Security Deposit Review
**Total Fields:** 9
**Key Fields:** _none_

## Programs Using This Table
- `z_get_security_deposit========ft`
- `zisfi0025`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VERTRAG` | CHAR | 10 |  | Contract |
| 2 | `ANLAGE` | CHAR | 10 |  | Installation |
| 3 | `EINZDAT_ALT` | DATS | 8 |  | Move-in date from legacy system |
| 4 | `EINZDAT` | DATS | 8 |  | Move-in date from legacy system |
| 5 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 6 | `ZTRIGGER` | LANG | 1 |  | Logon Language |
| 7 | `HIERARCHI` | LANG | 1 |  | Logon Language |
| 8 | `PARENT_VKONT` | CHAR | 12 |  | Contract Account Number |
| 9 | `ZDELETE` | LANG | 1 |  | Logon Language |
