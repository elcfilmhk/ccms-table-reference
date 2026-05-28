# ZISCSACCT
**Description:** Custom table for ZICS01 Full syn. - Account Level
**Total Fields:** 29
**Key Fields:** MANDT, VSTELLE, LGZUSATZ, HAUS, VKONTO, VERTRAG

## Programs Using This Table
- `ziscs0048`
- `ziscs0049`
- `ziscs0068`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `LGZUSATZ` | CHAR | 9 | 🔑 | Character field of 9 digits |
| 4 | `HAUS` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 5 | `VKONTO` | CHAR | 11 | 🔑 | Character Length 11 |
| 6 | `VERTRAG` | CHAR | 10 | 🔑 | Character Field Length = 10 |
| 7 | `CUSTNAME` | CHAR | 81 |  | Name of Business Partner |
| 8 | `IDTYPE` | CHAR | 6 |  | Character field of length 6 |
| 9 | `IDNO` | CHAR | 60 |  | R3A BP: Identification Number |
| 10 | `ATTCODE` | CHAR | 30 |  | 30 Characters |
| 11 | `TEL_NUMBER` | CHAR | 12 |  | Character Field of Length 12 |
| 12 | `CTEL_NUMBER` | CHAR | 20 |  | Char 20 |
| 13 | `DISTCODE` | CHAR | 5 |  | R/2 table |
| 14 | `STR_ERG2` | CHAR | 40 |  | Character field of length 40 |
| 15 | `STR_SUPPL1` | CHAR | 60 |  | Street and number |
| 16 | `HOUSE_NUM1` | CHAR | 10 |  | Character Field Length = 10 |
| 17 | `MC_STREET` | CHAR | 60 |  | Street |
| 18 | `CITY2` | CHAR | 40 |  | Character field of length 40 |
| 19 | `MC_CITY1` | CHAR | 40 |  | Character field of length 40 |
| 20 | `HAUS_NUM2` | CHAR | 10 |  | Character Field Length = 10 |
| 21 | `VBSART` | CHAR | 8 |  | Character field, 8 characters long |
| 22 | `CHI_CUSTNAME` | CHAR | 81 |  | Name of Business Partner |
| 23 | `STR_ERG4` | CHAR | 40 |  | Character field of length 40 |
| 24 | `CHI_STR_SUPPL1` | CHAR | 60 |  | Street and number |
| 25 | `CHI_HOUSE_NUM1` | CHAR | 10 |  | Character Field Length = 10 |
| 26 | `CHI_MC_STREET` | CHAR | 60 |  | Street |
| 27 | `CHI_CITY2` | CHAR | 40 |  | Character field of length 40 |
| 28 | `CHI_MC_CITY1` | CHAR | 40 |  | Character field of length 40 |
| 29 | `OPCODE` | CHAR | 1 |  | Single-Character Flag |
