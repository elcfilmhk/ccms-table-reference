# ZISCS0151_GET_CONTACTS_OUTPUT
**Description:** Output Struct of FM ZISCS0151_GET_CONTACTS
**Total Fields:** 51
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0151`
- `ziscs0151_get_contacts========ft`
- `ziscs0841`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 2 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 3 | `LANGU` | LANG | 1 |  | Language in connection with the contract account |
| 4 | `BPNAME` | CHAR | 100 |  | Text (100 characters) |
| 5 | `BPCNAME` | CHAR | 100 |  | Text (100 characters) |
| 6 | `ESERV_EMAIL_1` | CHAR | 50 |  | EBill email 1 |
| 7 | `ESERV_EMAIL_2` | CHAR | 50 |  | EBill email 2 |
| 8 | `ESERV_EMAIL_3` | CHAR | 50 |  | EBill email 3 |
| 9 | `ESERV_EMAIL_4` | CHAR | 50 |  | EBill email 4 |
| 10 | `ESERV_EMAIL_5` | CHAR | 50 |  | EBill email 5 |
| 11 | `ESERV_EMAIL_6` | CHAR | 50 |  | EBill email 6 |
| 12 | `ESERV_SMS` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 13 | `ESERV_SMS_1` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 14 | `ESERV_SMS_2` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 15 | `ESERV_SMS_3` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 16 | `ESERV_SMS_4` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 17 | `ESERV_SMS_5` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 18 | `ACCOUNT_BALANCE` | CHAR | 30 |  | 30 Characters |
| 19 | `EMKT_EMAIL` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 20 | `EMKT_SMS` | CHAR | 255 |  | Attribute 1 for Contact Information |
| 21 | `BP_TEL_STD` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 22 | `BP_MOB_STD` | CHAR | 30 |  | Telephone no.: dialling code+number |
| 23 | `BP_FAX_STD` | CHAR | 30 |  | Fax number: dialling code+number |
| 24 | `BP_EML_STD` | CHAR | 241 |  | E-Mail Address |
| 25 | `ANLAGE` | CHAR | 10 |  | Installation |
| 26 | `SERNR` | CHAR | 100 |  | Character 100 |
| 27 | `PRIORITY_EMAIL` | CHAR | 255 |  | Priority email address |
| 28 | `PRIORITY_EMAIL_SRC` | CHAR | 30 |  | Priority email Source |
| 29 | `PRIORITY_MOB` | CHAR | 255 |  | Priority Mobile number |
| 30 | `PRIORITY_MOB_SRC` | CHAR | 30 |  | Priority Mobile number Source |
| 31 | `NAME_CO` | CHAR | 40 |  | c/o name |
| 32 | `FLOOR` | CHAR | 10 |  | Floor in building |
| 33 | `ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 34 | `STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 35 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 36 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 37 | `STREET` | CHAR | 60 |  | Street |
| 38 | `CITY2` | CHAR | 40 |  | District |
| 39 | `REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 40 | `CITY1` | CHAR | 40 |  | City |
| 41 | `VSTELLE` | CHAR | 10 |  | Premise |
| 42 | `HAUS` | CHAR | 30 |  | Connection Object |
| 43 | `S_FLOOR` | CHAR | 10 |  | Floor in building |
| 44 | `S_ROOMNUMBER` | CHAR | 10 |  | Room or Apartment Number |
| 45 | `S_STR_SUPPL2` | CHAR | 40 |  | Street 3 |
| 46 | `S_STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 47 | `S_HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 48 | `S_STREET` | CHAR | 60 |  | Street |
| 49 | `S_CITY2` | CHAR | 40 |  | District |
| 50 | `S_REGION` | CHAR | 3 |  | Region (State, Province, County) |
| 51 | `S_CITY1` | CHAR | 40 |  | City |
