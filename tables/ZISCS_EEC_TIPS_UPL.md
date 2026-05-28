# ZISCS_EEC_TIPS_UPL
**Description:** Tips Up/Download
**Total Fields:** 17
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0380_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TXT_ID` | CHAR | 120 |  | Text ID (100) |
| 2 | `TXT_TY` | CHAR | 60 |  | Txt Type (50) |
| 3 | `EFF_FM_DT` | CHAR | 20 |  | Effective From DT Format YYYY.MM.DD hh:mm:ss |
| 4 | `EFF_EXP_DT` | CHAR | 20 |  | Effective Expiry DT Format YYYY.MM.DD hh:mm:ss |
| 5 | `DATE_MASK_FR` | CHAR | 5 |  | Date Mask From (MMYY) (4) |
| 6 | `DATE_MASK_TO` | CHAR | 5 |  | Date Mask To (MMYY) (4) |
| 7 | `IMAGE_CODE` | CHAR | 40 |  | Image Code (10) |
| 8 | `IMAGE_URL_EN` | CHAR | 256 |  | Sample Image URL(EN) |
| 9 | `IMAGE_URL_ZF` | CHAR | 256 |  | Sample Image URL(ZF) |
| 10 | `TEXT_EN` | CHAR | 600 |  | English Text (w/{?Vars}) (250) |
| 11 | `TEXT_EN2` | CHAR | 600 |  | English Text2 (w/{?Vars}) (250) |
| 12 | `TEXT_ZF` | CHAR | 600 |  | Chinese Text (w/{?Vars}) (80) |
| 13 | `TEXT_ZF2` | CHAR | 600 |  | Chinese Text2 (w/{?Vars}) (80) |
| 14 | `ACTION_URL_EN` | CHAR | 256 |  | Action URL(EN) |
| 15 | `ACTION_URL_ZF` | CHAR | 256 |  | Action URL(ZF) |
| 16 | `PRIORITY` | CHAR | 5 |  | Priority (4) |
| 17 | `TAG` | CHAR | 1000 |  | Tags (80 per Tag) Separate by ; |
