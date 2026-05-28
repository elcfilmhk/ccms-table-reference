# ZIS_ADDR_UPDATE
**Description:** Account Postal Address Update structure
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_upd_acctinfo===========ft`
- `zcl_z_bapi_upd_acctinf_mpc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `C_O_NAME` | CHAR | 40 |  | c/o name |
| 2 | `CITY` | CHAR | 40 |  | City |
| 3 | `DISTRICT` | CHAR | 40 |  | District |
| 4 | `STREET` | CHAR | 60 |  | Street |
| 5 | `HOUSE_NO` | CHAR | 10 |  | House Number |
| 6 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 7 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 8 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 9 | `ROOM_NO` | CHAR | 10 |  | Room or Apartment Number |
| 10 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 11 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 12 | `VALIDFROMDATE` | DATS | 8 |  | Validity Date (Valid From) |
| 13 | `VALIDTODATE` | DATS | 8 |  | Validity Date (Valid To) |
