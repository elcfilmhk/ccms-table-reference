# ZISFIREVRC
**Description:** The Revenue Summary Report Schedule 1 by Rate Category
**Total Fields:** 29
**Key Fields:** MANDT, ZRUNDATE, ZSECT, ZLINE

## Programs Using This Table
- `zisfi0032`
- `zisfi0043`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZRUNDATE` | DATS | 8 | 🔑 | Run Date |
| 3 | `ZSECT` | CHAR | 1 | 🔑 | Section |
| 4 | `ZLINE` | CHAR | 3 | 🔑 | Line |
| 5 | `ZLINETXT` | CHAR | 45 |  | Description |
| 6 | `ZDOMESTIC` | CURR | 13 |  | Net amount of billing line item |
| 7 | `ZSTAFF` | CURR | 13 |  | Net amount of billing line item |
| 8 | `ZELDERLY` | CURR | 13 |  | Net amount of billing line item |
| 9 | `ZSUBTOTAL1` | CURR | 13 |  | Net amount of billing line item |
| 10 | `ZGST` | CURR | 13 |  | Net amount of billing line item |
| 11 | `ZTRAFFIC` | CURR | 13 |  | Net amount of billing line item |
| 12 | `ZSUBTOTAL2` | CURR | 13 |  | Net amount of billing line item |
| 13 | `ZPLT` | CURR | 13 |  | Net amount of billing line item |
| 14 | `ZBULK` | CURR | 13 |  | Net amount of billing line item |
| 15 | `ZICE_AIR` | CURR | 13 |  | Net amount of billing line item |
| 16 | `ZLPT` | CURR | 13 |  | Net amount of billing line item |
| 17 | `ZLPT_HVSDR` | CURR | 13 |  | Net amount of billing line item |
| 18 | `ZSUBTOTAL3` | CURR | 13 |  | Net amount of billing line item |
| 19 | `ZGROUP` | CURR | 13 |  | Net amount of billing line item |
| 20 | `ZDUMMY` | CURR | 13 |  | Net amount of billing line item |
| 21 | `ZLOCALTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 22 | `ZLPT_OSSR` | CURR | 13 |  | Net amount of billing line item |
| 23 | `ZWHOLESALE` | CURR | 13 |  | Net amount of billing line item |
| 24 | `ZCHINATOTAL` | CURR | 13 |  | Net amount of billing line item |
| 25 | `ZOVERALLTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 26 | `ZCOLREF` | CURR | 13 |  | Net amount of billing line item |
| 27 | `ZCURRENCY` | CUKY | 5 |  | Transaction Currency |
| 28 | `ZCREATEDATE` | DATS | 8 |  | Date created |
| 29 | `ZCREATETIME` | TIMS | 6 |  | Time created |
