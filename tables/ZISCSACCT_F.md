# ZISCSACCT_F
**Description:** Custom table for ZICS01 Full syn. - Account Level
**Total Fields:** 32
**Key Fields:** MANDT, VSTELLE, HAUS, VKONTO, VERTRAG

## Programs Using This Table
- `ziscs0368`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `HAUS` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 4 | `VKONTO` | CHAR | 12 | 🔑 | Character Field of Length 12 |
| 5 | `VERTRAG` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 6 | `CUSTNAME` | CHAR | 81 |  | Name of Business Partner |
| 7 | `ATTCODE` | CHAR | 30 |  | 30 Characters |
| 8 | `TEL_NUMBER` | CHAR | 12 |  | Character Field of Length 12 |
| 9 | `CTEL_NUMBER` | CHAR | 20 |  | Char 20 |
| 10 | `DISTCODE` | CHAR | 5 |  | R/2 table |
| 11 | `STR_ERG2` | CHAR | 40 |  | Character field of length 40 |
| 12 | `STR_SUPPL1` | CHAR | 60 |  | Street and number |
| 13 | `HOUSE_NUM1` | CHAR | 10 |  | Character Field Length = 10 |
| 14 | `MC_STREET` | CHAR | 60 |  | Street |
| 15 | `CITY2` | CHAR | 40 |  | Character field of length 40 |
| 16 | `MC_CITY1` | CHAR | 40 |  | Character field of length 40 |
| 17 | `HAUS_NUM2` | CHAR | 10 |  | Character Field Length = 10 |
| 18 | `VBSART` | CHAR | 8 |  | Character field, 8 characters long |
| 19 | `CHI_CUSTNAME` | CHAR | 81 |  | Name of Business Partner |
| 20 | `STR_ERG4` | CHAR | 40 |  | Character field of length 40 |
| 21 | `CHI_STR_SUPPL1` | CHAR | 60 |  | Street and number |
| 22 | `CHI_HOUSE_NUM1` | CHAR | 10 |  | Character Field Length = 10 |
| 23 | `CHI_MC_STREET` | CHAR | 60 |  | Street |
| 24 | `CHI_CITY2` | CHAR | 40 |  | Character field of length 40 |
| 25 | `CHI_MC_CITY1` | CHAR | 40 |  | Character field of length 40 |
| 26 | `ROOMNUMBER` | CHAR | 10 |  | Character Field Length = 10 |
| 27 | `FLOOR` | CHAR | 10 |  | Character Field Length = 10 |
| 28 | `AKLASSE` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 29 | `TARIFTYP` | CHAR | 10 |  | Character Field Length = 10 |
| 30 | `ZZ_LIFE_SUPPORT` | CHAR | 1 |  | Life Support Indicator |
| 31 | `KTOKL` | CHAR | 4 |  | Account class |
| 32 | `TYPE` | CHAR | 1 |  | Business Partner Category |
