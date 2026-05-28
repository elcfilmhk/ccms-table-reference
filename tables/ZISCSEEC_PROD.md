# ZISCSEEC_PROD
**Description:** Eco Point Product Master
**Total Fields:** 14
**Key Fields:** MANDT, PROD_CODE

## Programs Using This Table
- `ziscs0471_eec`
- `ziscs0472_eec`
- `ziscs0475_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROD_CODE` | CHAR | 50 | 🔑 | EcoPoint Product Code |
| 3 | `PROD_NAME_EN` | CHAR | 500 |  | Product Name (EN) |
| 4 | `PROD_NAME_ZF` | CHAR | 500 |  | Product Name (ZF) |
| 5 | `PROD_DESC_EN` | CHAR | 500 |  | Description(EN) |
| 6 | `PROD_DESC_ZF` | CHAR | 300 |  | Description(ZF) |
| 7 | `MERC_CODE` | CHAR | 100 |  | Sponsor/Merchant Code |
| 8 | `INFINITE_STOCK` | CHAR | 1 |  | Infinite Stock Flag |
| 9 | `PROD_TERMS_URL_EN` | CHAR | 255 |  | EcoPoint Product Terms & Conditions URL(EN) |
| 10 | `PROD_TERMS_URL_ZF` | CHAR | 255 |  | EcoPoint Product Terms & Conditions URL(ZF) |
| 11 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 12 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 13 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 14 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
