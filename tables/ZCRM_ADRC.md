# ZCRM_ADRC
**Description:** For address data comparison use
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `ziscrmaddrcomp`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `ADDRNUMBER` | CHAR | 10 |  | Address Number |
| 2 | `DATE_FROM` | DATS | 8 |  | Valid-from date - in current Release only 00010101 possible |
| 3 | `NATION` | CHAR | 1 |  | Version ID for International Addresses |
| 4 | `NAME_CO` | CHAR | 40 |  | c/o name |
| 5 | `CITY1` | CHAR | 40 |  | City |
| 6 | `CITY2` | CHAR | 40 |  | District |
| 7 | `STREET` | CHAR | 60 |  | Street |
| 8 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 9 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 10 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
