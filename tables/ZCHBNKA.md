# ZCHBNKA
**Description:** Bank master record with chinese bank name
**Total Fields:** 21
**Key Fields:** _none_

## Programs Using This Table
- `zrfbkvz00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `BANKS` | CHAR | 3 |  | Bank Country Key |
| 2 | `BANKL` | CHAR | 15 |  | Bank Keys |
| 3 | `ERDAT` | DATS | 8 |  | Date on which the record was created |
| 4 | `ERNAM` | CHAR | 12 |  | Name of person who created the object |
| 5 | `BANKA` | CHAR | 60 |  | Name of bank |
| 6 | `PROVZ` | CHAR | 3 |  | Region (State, Province, County) |
| 7 | `STRAS` | CHAR | 35 |  | Street and House Number |
| 8 | `ORT01` | CHAR | 35 |  | City |
| 9 | `SWIFT` | CHAR | 11 |  | SWIFT/BIC for International Payments |
| 10 | `BGRUP` | CHAR | 2 |  | Bank group (bank network) |
| 11 | `XPGRO` | CHAR | 1 |  | Post Office Bank Current Account |
| 12 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 13 | `BNKLZ` | CHAR | 15 |  | Bank number |
| 14 | `PSKTO` | CHAR | 16 |  | Post office bank current account number |
| 15 | `ADRNR` | CHAR | 10 |  | Address Number |
| 16 | `BRNCH` | CHAR | 40 |  | Bank Branch |
| 17 | `CHKME` | CHAR | 4 |  | Check digit calculation method |
| 18 | `VERS` | CHAR | 3 |  | Format of File with Bank Data |
| 19 | `BICKY` | CHAR | 12 |  | Key of a BIC+ data record (Swift) |
| 20 | `RCCODE` | CHAR | 15 |  | Routing control code |
| 21 | `DESCR` | CHAR | 60 |  | Description in Chinese |
