# ZISCSPOSTBILL
**Description:** Account list of postal bill delivery
**Total Fields:** 52
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `ziscs0467`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `BPNAME` | CHAR | 81 |  | Business Partner name |
| 5 | `BPCNAME` | CHAR | 40 |  | Business Partner Chinese name |
| 6 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 7 | `KTOKL` | CHAR | 4 |  | Account class |
| 8 | `SENDCONTROL_GP` | CHAR | 4 |  | Dispatch control for original customer |
| 9 | `NAME_CO` | CHAR | 40 |  | c/o name |
| 10 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 11 | `ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 12 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 13 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 14 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 15 | `STREET` | CHAR | 60 |  | Street |
| 16 | `CITY2` | CHAR | 40 |  | District |
| 17 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 18 | `CITY1` | CHAR | 40 |  | City |
| 19 | `VSTELLE` | CHAR | 10 |  | Premise |
| 20 | `HAUS` | CHAR | 30 |  | Connection Object |
| 21 | `ZBA` | CHAR | 4 |  | BP ownership |
| 22 | `CA_OWNER` | CHAR | 4 |  | CA ownership |
| 23 | `PARTNER2` | CHAR | 10 |  | Business Partner Number |
| 24 | `PARTNER` | CHAR | 12 |  | User Name in User Master Record |
| 25 | `S_FLOOR` | CHAR | 10 |  | Floor in building |
| 26 | `S_ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 27 | `S_STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 28 | `S_STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 29 | `S_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 30 | `S_STREET` | CHAR | 60 |  | Street |
| 31 | `S_CITY2` | CHAR | 40 |  | District |
| 32 | `S_REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 33 | `CONTACT1` | CHAR | 30 |  | Contact 1 |
| 34 | `CONTACT2` | CHAR | 30 |  | Contact 2 |
| 35 | `MOBILE` | CHAR | 30 |  | Mobile |
| 36 | `FAX1` | CHAR | 30 |  | Fax 1 |
| 37 | `FAX2` | CHAR | 30 |  | Fax 2 |
| 38 | `EMAIL1` | CHAR | 241 |  | E-Mail Address |
| 39 | `EMAIL2` | CHAR | 241 |  | E-Mail Address |
| 40 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 41 | `WEBSERVICE` | CHAR | 1 |  | Web Service |
| 42 | `PAYMETHOD` | CHAR | 1 |  | Incoming Payment Method |
| 43 | `SEGMENT_LABEL` | CHAR | 1 |  | Segment label |
| 44 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 45 | `AUSZDAT` | DATS | 8 |  | Move-Out Date |
| 46 | `ABWVK` | CHAR | 12 |  | Alternative contract account for collective bills |
| 47 | `ZZDELIVERY` | CHAR | 1 |  | Delivery Method |
| 48 | `LAST_BILL_DATE` | DATS | 8 |  | Last Billing Date |
| 49 | `LAST_BILL_AMOUNT` | CURR | 13 |  | Last Billing Amount |
| 50 | `LAST_BILL_WAER` | CUKY | 5 |  | Last Billing Currency |
| 51 | `LAST_BILL_DUE_DATE` | DATS | 8 |  | Last Billing Due Date |
| 52 | `LAST_BILL_ADDR_CHANGE_DATE` | DATS | 8 |  | Last Billing Address Change Date |
