# ZISCSMONTHREC
**Description:** Monthly Record
**Total Fields:** 20
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0200`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 4 | `ARBPL` | CHAR | 8 |  | Work Center |
| 5 | `PARNR` | CHAR | 12 |  | User Name |
| 6 | `EQFNR` | CHAR | 30 |  | Sort field |
| 7 | `AUART` | CHAR | 4 |  | Sales Document Type |
| 8 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 9 | `PRIOK` | CHAR | 1 |  | Priority |
| 10 | `HOUSE_NUM1` | CHAR | 10 |  | House Number |
| 11 | `STREET` | CHAR | 60 |  | Street |
| 12 | `STR_SUPPL1` | CHAR | 40 |  | Street 2 |
| 13 | `CITY2` | CHAR | 40 |  | District |
| 14 | `USER_STATUS` | CHAR | 40 |  | System status line |
| 15 | `TPLMA` | CHAR | 30 |  | Connection Object |
| 16 | `INGPR` | CHAR | 3 |  | Planner Group for Customer Service and Plant Maintenance |
| 17 | `OBJNR` | CHAR | 22 |  | Object number |
| 18 | `TPLNR` | CHAR | 30 |  | Functional Location |
| 19 | `BC` | CHAR | 8 |  | Business Center |
| 20 | `REGION` | CHAR | 15 |  | Region |
