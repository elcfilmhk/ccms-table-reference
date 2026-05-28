# ZISCS_EEC_PROD_UPL
**Description:** Product Info Up/Download
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0471_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PROD_CODE` | CHAR | 60 |  | Product Code (50) |
| 2 | `MERC_CODE` | CHAR | 110 |  | Merchant Code (100) |
| 3 | `PROD_NAME_EN` | CHAR | 260 |  | English Product Name(250) |
| 4 | `PROD_NAME_ZF` | CHAR | 90 |  | Chinese Product Name(80) |
| 5 | `IMAGE_CODE` | CHAR | 40 |  | Image Code (30) |
| 6 | `IMAGE_URL_EN` | CHAR | 256 |  | Eng Image URL (250) |
| 7 | `IMAGE_URL_ZF` | CHAR | 256 |  | Chi Image URL (250) |
| 8 | `TEXT_EN1` | CHAR | 260 |  | English Product Description (250) |
| 9 | `TEXT_EN2` | CHAR | 260 |  | English Product Description2 (250) |
| 10 | `TEXT_ZF1` | CHAR | 90 |  | Chinese Product Description (80) |
| 11 | `TEXT_ZF2` | CHAR | 90 |  | Chinese Product Description2 (80) |
| 12 | `PROD_TERMS_URL_EN` | CHAR | 256 |  | English T&C URL (250) |
| 13 | `PROD_TERMS_URL_ZF` | CHAR | 256 |  | Chinese T&C URL (250) |
| 14 | `INFINITE_STOCK` | CHAR | 2 |  | 'X': Infinite Stock (1) |
| 15 | `TAG` | CHAR | 1000 |  | Tags (80 per Tag) Separate by ; |
