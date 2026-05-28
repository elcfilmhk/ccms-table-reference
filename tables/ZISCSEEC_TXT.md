# ZISCSEEC_TXT
**Description:** Taggable-Texts Library
**Total Fields:** 19
**Key Fields:** MANDT, TXT_ID

## Programs Using This Table
- `ziscs0380_eec`
- `ziscs0471_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXT_ID` | CHAR | 100 | 🔑 | Text ID |
| 3 | `TXT_TY` | CHAR | 50 |  | Text Type |
| 4 | `EFF_FM_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `DATE_MASK_FR` | CHAR | 4 |  | Date Mask (MMDD) |
| 7 | `DATE_MASK_TO` | CHAR | 4 |  | Date Mask (MMDD) |
| 8 | `IMAGE_CODE` | CHAR | 30 |  | Image Code |
| 9 | `IMAGE_URL_EN` | CHAR | 255 |  | Sample Image URL(EN) |
| 10 | `IMAGE_URL_ZF` | CHAR | 255 |  | Sample Image URL(ZF) |
| 11 | `TEXT_EN` | CHAR | 500 |  | Case-sensitive Text of 500 length |
| 12 | `TEXT_ZF` | CHAR | 300 |  | Case-sensitive Text of 300 length |
| 13 | `ACTION_URL_EN` | CHAR | 255 |  | Action URL(EN) |
| 14 | `ACTION_URL_ZF` | CHAR | 255 |  | Action URL(ZF) |
| 15 | `PRIORITY` | INT4 | 10 |  | Natural number |
| 16 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 17 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 18 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 19 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
