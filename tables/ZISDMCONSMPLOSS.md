# ZISDMCONSMPLOSS
**Description:** Comsumption Loss Details of Each Month
**Total Fields:** 30
**Key Fields:** MANDT, ID, ZYEAR, ZMONTH, OLD_ACCT, NEW_ACCT, DEVICE

## Programs Using This Table
- `zisdm0136`
- `zisdm0136a`
- `zisdm0136b`
- `zisdm0136c`
- `zisdm0136d`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ID` | CHAR | 2 | 🔑 | ID |
| 3 | `ZYEAR` | CHAR | 4 | 🔑 | Year |
| 4 | `ZMONTH` | CHAR | 2 | 🔑 | Month |
| 5 | `OLD_ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `NEW_ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 7 | `DEVICE` | CHAR | 18 | 🔑 | Device |
| 8 | `OLD_CUST_NAME` | CHAR | 50 |  | Name (surname/first name for nat. persons, company name) |
| 9 | `OLD_ORG_NAME1` | CHAR | 40 |  | Name 1 of organization |
| 10 | `OLD_ORG_NAME2` | CHAR | 40 |  | Name 2 of organization |
| 11 | `OLD_ORG_NAME3` | CHAR | 40 |  | Name 3 of organization |
| 12 | `OLD_ORG_NAME4` | CHAR | 40 |  | Name 4 of organization |
| 13 | `OLD_TARIFTYP` | CHAR | 10 |  | Rate category |
| 14 | `OLD_ACCTCLASS` | CHAR | 4 |  | Account class |
| 15 | `NEW_CUST_NAME` | CHAR | 50 |  | Name (surname/first name for nat. persons, company name) |
| 16 | `NEW_ORG_NAME1` | CHAR | 40 |  | Name 1 of organization |
| 17 | `NEW_ORG_NAME2` | CHAR | 40 |  | Name 2 of organization |
| 18 | `NEW_ORG_NAME3` | CHAR | 40 |  | Name 3 of organization |
| 19 | `NEW_ORG_NAME4` | CHAR | 40 |  | Name 4 of organization |
| 20 | `NEW_TARIFTYP` | CHAR | 10 |  | Rate category |
| 21 | `NEW_ACCTCLASS` | CHAR | 4 |  | Account class |
| 22 | `CW` | NUMC | 4 |  | Creditworthiness |
| 23 | `UNITLOSS` | DEC | 10 |  | Consumption loss |
| 24 | `MODM_READING` | DEC | 31 |  | Previous meter reading |
| 25 | `MIRM_READING` | DEC | 31 |  | Meter reading recorded |
| 26 | `INIT_ID` | CHAR | 12 |  | Name of Person Who Created the Object |
| 27 | `MO_DATE` | DATS | 8 |  | Date |
| 28 | `MIRM_DATE` | DATS | 8 |  | Date |
| 29 | `MOMI_DURATION` | DEC | 5 |  | Duration |
| 30 | `ROUND` | CHAR | 1 |  | Round clock indicator |
