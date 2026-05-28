# ZISCS_CON_CA_LIST
**Description:** structure of consolidate CA
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_get_con_ca_by_bp=======ft`
- `zcl_z_bapi_get_con_ca__mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PARTNER` | CHAR | 10 |  | Business Partner Number |
| 2 | `IDNUMBER` | CHAR | 60 |  | Identification Number |
| 3 | `IDTYPE` | CHAR | 6 |  | Identification Type |
| 4 | `BPNAME` | CHAR | 80 |  | BP Full Name |
| 5 | `ACCT_TYPE` | CHAR | 5 |  | Account type |
| 6 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 9 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 10 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 11 | `KTOKL` | CHAR | 4 |  | Account class |
