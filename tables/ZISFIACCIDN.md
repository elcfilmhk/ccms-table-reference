# ZISFIACCIDN
**Description:** The Revenue Summary Report Schedule 2 by Account Class
**Total Fields:** 21
**Key Fields:** MANDT, ZRUNDATE, ZPOSDATE, ZINDEX

## Programs Using This Table
- `zisfi0086`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZRUNDATE` | DATS | 8 | 🔑 | Run Date |
| 3 | `ZPOSDATE` | DATS | 8 | 🔑 | Posting Date |
| 4 | `ZINDEX` | NUMC | 3 | 🔑 | Index |
| 5 | `ZFLAG` | CHAR | 1 |  | Flag |
| 6 | `ZTEXT` | CHAR | 35 |  | Text |
| 7 | `ZCOLOR` | NUMC | 3 |  | Color |
| 8 | `ZFIELD1` | CURR | 13 |  | Amount |
| 9 | `ZFIELD2` | CURR | 13 |  | Amount |
| 10 | `ZFIELD3` | CURR | 13 |  | Amount |
| 11 | `ZFIELD4` | CURR | 13 |  | Amount |
| 12 | `ZFIELD5` | CURR | 13 |  | Amount |
| 13 | `ZFIELD6` | CURR | 13 |  | Amount |
| 14 | `ZFIELD7` | CURR | 13 |  | Amount |
| 15 | `ZFIELD8` | CURR | 13 |  | Amount |
| 16 | `ZFIELD9` | CURR | 13 |  | Amount |
| 17 | `ZFIELD10` | CURR | 13 |  | Amount |
| 18 | `ZFIELD11` | CURR | 13 |  | Amount |
| 19 | `ZFIELD12` | CURR | 13 |  | Amount |
| 20 | `ZCREATEDATE` | DATS | 8 |  | Date created |
| 21 | `ZCREATETIME` | TIMS | 6 |  | Time created |
