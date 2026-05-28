# ZNEWPOSTALADDR
**Description:** New postal address to Business Partner
**Total Fields:** 18
**Key Fields:** MANDT, BP, ACCT, MO

## Programs Using This Table
- `ziscs0184`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BP` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `MO` | DATS | 8 | 🔑 | Move-Out Date |
| 5 | `ROOM` | CHAR | 10 |  | Room or Apartment Number |
| 6 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 7 | `CO` | CHAR | 40 |  | c/o name |
| 8 | `STREET3` | CHAR | 40 |  | Street 3 |
| 9 | `STREET2` | CHAR | 40 |  | Street 2 |
| 10 | `STREET` | CHAR | 60 |  | Street |
| 11 | `HOUSENUM` | CHAR | 10 |  | House Number |
| 12 | `CITY` | CHAR | 40 |  | City |
| 13 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 14 | `COUNTRY` | CHAR | 3 |  | Country Key |
| 15 | `DISTRICT` | CHAR | 40 |  | District |
| 16 | `NATION` | CHAR | 1 |  | Version ID for International Addresses |
| 17 | `STATUS` | CHAR | 1 |  | Update Status |
| 18 | `ACTION` | CHAR | 1 |  | Action |
