# ZISCS_EEC_GET_TXT_OUTPUT
**Description:** List of Texts retrieved
**Total Fields:** 12
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0390_eec`
- `ziscs0475_eec`
- `ziscseec_eo_get_txt===========ft`
- `ziscseec_eo_get_txt_tk_ws=====ft`
- `ziscseec_eo_get_txt_ws========ft`
- `ziscseec_get_txt==============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TXT_ID` | CHAR | 100 |  | Text ID |
| 2 | `TXT_TY` | CHAR | 50 |  | Text Type |
| 3 | `EFF_FM_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 4 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `IMAGE_CODE` | CHAR | 30 |  | Image Code |
| 6 | `IMAGE_URL_EN` | CHAR | 255 |  | Sample Image URL(EN) |
| 7 | `IMAGE_URL_ZF` | CHAR | 255 |  | Sample Image URL(ZF) |
| 8 | `TEXT_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 9 | `TEXT_ZF` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 10 | `ACTION_URL_EN` | CHAR | 255 |  | Action URL(EN) |
| 11 | `ACTION_URL_ZF` | CHAR | 255 |  | Action URL(ZF) |
| 12 | `PRIORITY` | INT4 | 10 |  | Natural number |
