# ZISSDRBSBONHDR
**Description:** Residential Bonus Scheme Bonus Header
**Total Fields:** 75
**Key Fields:** MANDT, SCHNO

## Programs Using This Table
- `zisfi0138`
- `zisfi0246`
- `zisfi0247`
- `zissd00076`
- `zissd00077`
- `zissd00105`
- `zissd00109`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHNO` | CHAR | 10 | 🔑 | Bonus Scheme Number |
| 3 | `APPNO` | CHAR | 10 |  | Application no. |
| 4 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `VSTEL` | CHAR | 10 |  | Premise |
| 7 | `APDAT` | DATS | 8 |  | Application Date |
| 8 | `CRDAT` | DATS | 8 |  | Creation date |
| 9 | `CRUSR` | CHAR | 12 |  | Created By |
| 10 | `LCDAT` | DATS | 8 |  | Last change date |
| 11 | `LCUSR` | CHAR | 12 |  | Last change by |
| 12 | `STATU` | CHAR | 2 |  | Status |
| 13 | `BONSC` | CHAR | 10 |  | Scheme Type |
| 14 | `TTOCA` | CHAR | 10 |  | Transfer bonus to CA |
| 15 | `TFRCA` | CHAR | 10 |  | Transfer bonus from CA |
| 16 | `CNTPS` | CHAR | 30 |  | Contact person |
| 17 | `CNTNO` | CHAR | 15 |  | Contact person number |
| 18 | `HHSIZ` | CHAR | 4 |  | Household size |
| 19 | `MAOWS` | CHAR | 1 |  | Washer |
| 20 | `MAODY` | CHAR | 1 |  | Clothes dryer |
| 21 | `MAOWD` | CHAR | 1 |  | 2-in-1 washer/dryer |
| 22 | `MAOAC` | CHAR | 1 |  | Air-conditioner |
| 23 | `MAOHT` | CHAR | 1 |  | Space heater |
| 24 | `EWBND` | CHAR | 20 |  | EWH Brand |
| 25 | `EWTYP` | CHAR | 20 |  | EWH Type |
| 26 | `EWCHL` | CHAR | 20 |  | EWH Purchase channel |
| 27 | `EWINS` | DATS | 8 |  | EWH installation date |
| 28 | `ICBND` | CHAR | 20 |  | IC Brand |
| 29 | `ICTYP` | CHAR | 20 |  | IC Type |
| 30 | `ICCHL` | CHAR | 20 |  | IC Purchase channel |
| 31 | `ICINS` | DATS | 8 |  | IC installation date |
| 32 | `CPYSI` | CHAR | 1 |  | Copy of Sales Invoice |
| 33 | `CPYIN` | CHAR | 1 |  | Copy of Install note |
| 34 | `EDMSL` | CHAR | 100 |  | EDMS link for other documentation |
| 35 | `PCDAT` | DATS | 8 |  | Pre-site check date |
| 36 | `PCUSR` | CHAR | 10 |  | Pre-site check staff no. |
| 37 | `INVCHECK` | NUMC | 1 |  | Invoice checked |
| 38 | `WARRCHECK` | NUMC | 1 |  | Warranty checked |
| 39 | `SHOPCHECK` | NUMC | 1 |  | Shop checked |
| 40 | `POSTCHECK` | NUMC | 1 |  | Post checked |
| 41 | `POSTSITEDATE` | DATS | 8 |  | Post-site check date |
| 42 | `POSTSITESTAFF` | CHAR | 10 |  | Post-site check staff no. |
| 43 | `POSTPRODUCTEXIST` | CHAR | 10 |  | Post product exist |
| 44 | `RESETCANCEL` | CHAR | 1 |  | Reset Cancel |
| 45 | `HOTLINE` | CHAR | 30 |  | Hot line location |
| 46 | `EWSHOP` | CHAR | 50 |  | Shop |
| 47 | `EWSHOPDISTRICT` | CHAR | 3 |  | Shop District |
| 48 | `EWSHOPADDR` | CHAR | 50 |  | Shop Address |
| 49 | `EWSHOPTEL` | CHAR | 10 |  | Shop Telephone |
| 50 | `EWPRICE` | CHAR | 10 |  | RBS EWH Price |
| 51 | `ICSHOP` | CHAR | 50 |  | Shop |
| 52 | `ICSHOPDISTRICT` | CHAR | 3 |  | Shop District |
| 53 | `ICSHOPADDR` | CHAR | 50 |  | Shop Address |
| 54 | `ICSHOPTEL` | CHAR | 10 |  | Shop Telephone |
| 55 | `ICPRICE` | CHAR | 10 |  | RBS IC Price |
| 56 | `EWHOTHBND` | CHAR | 20 |  | EWH Other Brand |
| 57 | `ICOTHBND` | CHAR | 20 |  | IC Other Brand |
| 58 | `G1_BRAND` | CHAR | 20 |  | Grade 1 Appliance - Brand |
| 59 | `G1_MODEL_NO` | CHAR | 20 |  | Grade 1 Appliance - Model Number |
| 60 | `G1_TYPE` | CHAR | 20 |  | Grade 1 Appliance - Type |
| 61 | `G1_PRICE` | CHAR | 10 |  | Grade 1 Appliance - Price |
| 62 | `G1_SHOP` | CHAR | 50 |  | Grade 1 Appliance - Shop Name |
| 63 | `G1_SHOP_DISTRICT` | CHAR | 3 |  | Grade 1 Appliance - Shop District |
| 64 | `G1_SHOP_PHONE` | CHAR | 10 |  | Grade 1 Appliance - Shop Telephone Number |
| 65 | `G1_SHOP_ADDRESS` | CHAR | 50 |  | Grade 1 Appliance - Shop Address |
| 66 | `G1_CHANNEL` | CHAR | 20 |  | Grade 1 Appliance - Purchase Channel |
| 67 | `RSDAT` | DATS | 8 |  | Reset cancel date |
| 68 | `SUB_SCHEME` | CHAR | 4 |  | Sub Scheme |
| 69 | `SCHEME` | CHAR | 10 |  | Scheme |
| 70 | `EWHINT_REDATE` | DATS | 8 |  | EWH Intermediary Rebate date |
| 71 | `EWHINT_SO` | CHAR | 10 |  | EWH Intermediary Sales Order |
| 72 | `EWHINT_AMOUNT` | CURR | 11 |  | EWH Intermediary Rebate Amount |
| 73 | `ICINT_REDATE` | DATS | 8 |  | IC Intermediary Rebate date |
| 74 | `ICINT_SO` | CHAR | 10 |  | IC Intermediary Sales Order |
| 75 | `ICINT_AMOUNT` | CURR | 11 |  | IC Intermediary Rebate Amount |
