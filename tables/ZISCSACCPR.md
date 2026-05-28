# ZISCSACCPR
**Description:** Structure for Contract Account No. and Premise ID
**Total Fields:** 8
**Key Fields:** _none_

## Programs Using This Table
- `z_get_ccs_ca_info=============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ZZTCOMJBNO` | CHAR | 13 |  | Job number of TCOM |
| 2 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 3 | `VSTELLE` | CHAR | 10 |  | Premise |
| 4 | `LGZUSATZ` | CHAR | 40 |  | Additional Information on Location |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `ZZBPADDRESS1` | CHAR | 210 |  | Business Partner Address in CRM |
| 7 | `XLOEK` | CHAR | 1 |  | Item is deleted |
| 8 | `TYPE` | CHAR | 1 |  | Business partner category |
