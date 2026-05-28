# ZISFIREVRCN
**Description:** The Revenue Summary Report Schedule 1 by Rate Category
**Total Fields:** 33
**Key Fields:** MANDT, ZRUNDATE, ZPOSDATE, ZSECT, ZLINE

## Programs Using This Table
- `zisbifi_recon`
- `zisfi0084`
- `zisfi0084t`
- `zisfi0086`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZRUNDATE` | DATS | 8 | 🔑 | Run Date |
| 3 | `ZPOSDATE` | DATS | 8 | 🔑 | Posting Date |
| 4 | `ZSECT` | CHAR | 1 | 🔑 | Section |
| 5 | `ZLINE` | CHAR | 3 | 🔑 | Line |
| 6 | `ZLINETXT` | CHAR | 45 |  | Description |
| 7 | `ZDOMESTIC` | CURR | 13 |  | Net amount of billing line item |
| 8 | `ZSTAFF` | CURR | 13 |  | Net amount of billing line item |
| 9 | `ZELDERLY` | CURR | 13 |  | Net amount of billing line item |
| 10 | `ZSUBTOTAL1` | CURR | 13 |  | Net amount of billing line item |
| 11 | `ZGST` | CURR | 13 |  | Net amount of billing line item |
| 12 | `ZTRAFFIC` | CURR | 13 |  | Net amount of billing line item |
| 13 | `ZEVFLAT` | CURR | 13 |  | Net amount of billing line item |
| 14 | `ZEVTOU` | CURR | 13 |  | Net amount of billing line item |
| 15 | `ZSUBTOTAL2` | CURR | 13 |  | Net amount of billing line item |
| 16 | `ZPLT` | CURR | 13 |  | Net amount of billing line item |
| 17 | `ZEV` | CURR | 13 |  | Net amount of billing line item |
| 18 | `ZBULK` | CURR | 13 |  | Net amount of billing line item |
| 19 | `ZICE_AIR` | CURR | 13 |  | Net amount of billing line item |
| 20 | `ZLPT` | CURR | 13 |  | Net amount of billing line item |
| 21 | `ZLPT_HVSDR` | CURR | 13 |  | Net amount of billing line item |
| 22 | `ZSUBTOTAL3` | CURR | 13 |  | Net amount of billing line item |
| 23 | `ZGROUP` | CURR | 13 |  | Net amount of billing line item |
| 24 | `ZDUMMY` | CURR | 13 |  | Net amount of billing line item |
| 25 | `ZLOCALTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 26 | `ZLPT_OSSR` | CURR | 13 |  | Net amount of billing line item |
| 27 | `ZWHOLESALE` | CURR | 13 |  | Net amount of billing line item |
| 28 | `ZCHINATOTAL` | CURR | 13 |  | Net amount of billing line item |
| 29 | `ZOVERALLTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 30 | `ZCOLREF` | CURR | 13 |  | Net amount of billing line item |
| 31 | `ZCURRENCY` | CUKY | 5 |  | Transaction Currency |
| 32 | `ZCREATEDATE` | DATS | 8 |  | Date created |
| 33 | `ZCREATETIME` | TIMS | 6 |  | Time created |
