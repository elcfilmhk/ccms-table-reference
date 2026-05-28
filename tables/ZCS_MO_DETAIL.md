# ZCS_MO_DETAIL
**Description:** Structure for get move-out date by premise ID
**Total Fields:** 6
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_mo_date================ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 3 | `VSTELLE` | CHAR | 10 |  | Premise |
| 4 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 5 | `ZZPAUSZDAT` | DATS | 8 |  | Pending Move-Out Date |
| 6 | `EINZDAT` | DATS | 8 |  | Move-In Date |
