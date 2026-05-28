# ZISFIREVACN
**Description:** The Revenue Summary Report Schedule 1 by Account Class
**Total Fields:** 23
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
| 7 | `Z01` | CURR | 13 |  | Net amount of billing line item |
| 8 | `Z02` | CURR | 13 |  | Net amount of billing line item |
| 9 | `Z03` | CURR | 13 |  | Net amount of billing line item |
| 10 | `ZLIGHT` | CURR | 13 |  | Net amount of billing line item |
| 11 | `ZEV` | CURR | 13 |  | Net amount of billing line item |
| 12 | `Z04` | CURR | 13 |  | Net amount of billing line item |
| 13 | `ZGROUP` | CURR | 13 |  | Net amount of billing line item |
| 14 | `ZDUMMY` | CURR | 13 |  | Net amount of billing line item |
| 15 | `ZLOCALTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 16 | `Z05` | CURR | 13 |  | Net amount of billing line item |
| 17 | `Z06` | CURR | 13 |  | Net amount of billing line item |
| 18 | `ZCHINATOTAL` | CURR | 13 |  | Net amount of billing line item |
| 19 | `ZOVERALLTOTAL` | CURR | 13 |  | Net amount of billing line item |
| 20 | `ZCOLREF` | CURR | 13 |  | Net amount of billing line item |
| 21 | `ZCURRENCY` | CUKY | 5 |  | Transaction Currency |
| 22 | `ZCREATEDATE` | DATS | 8 |  | Date created |
| 23 | `ZCREATETIME` | TIMS | 6 |  | Time created |
