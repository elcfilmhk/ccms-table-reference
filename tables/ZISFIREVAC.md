# ZISFIREVAC
**Description:** The Revenue Summary Report Schedule 1 by Account Class
**Total Fields:** 21
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
| 6 | `Z01` | CURR | 13 |  | Net amount of billing line item |
| 7 | `Z02` | CURR | 13 |  | Net amount of billing line item |
| 8 | `Z03` | CURR | 13 |  | Net amount of billing line item |
| 9 | `ZLIGHT` | CURR | 13 |  | Net amount of billing line item |
| 10 | `Z04` | CURR | 13 |  | Net amount of billing line item |
| 11 | `ZGROUP` | CURR | 13 |  | Net amount of billing line item |
| 12 | `ZDUMMY` | CURR | 13 |  | Net amount of billing line item |
| 13 | `ZLOCALTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 14 | `Z05` | CURR | 13 |  | Net amount of billing line item |
| 15 | `Z06` | CURR | 13 |  | Net amount of billing line item |
| 16 | `ZCHINATOTAL` | CURR | 13 |  | Net amount of billing line item |
| 17 | `ZOVERALLTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 18 | `ZCOLREF` | CURR | 13 |  | Net amount of billing line item |
| 19 | `ZCURRENCY` | CUKY | 5 |  | Transaction Currency |
| 20 | `ZCREATEDATE` | DATS | 8 |  | Date created |
| 21 | `ZCREATETIME` | TIMS | 6 |  | Time created |
