# ZISU_PRICE_TEMPLATE_S
**Description:** Price structure template
**Total Fields:** 32
**Key Fields:** _none_

## Programs Using This Table
- `zcl_isu_price`
- `zisfi0297`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `PRICE_TEMPLATE` | CHAR | 10 |  | Price |
| 2 | `PREIS` | CHAR | 10 |  | Price |
| 3 | `TEXT30` | CHAR | 50 |  | Text Field |
| 4 | `PREISTYP` | CHAR | 1 |  | Price category |
| 5 | `PREISTUF` | CHAR | 10 |  | Price level |
| 6 | `SPARTE` | CHAR | 2 |  | Division |
| 7 | `MASS` | UNIT | 3 |  | Unit of Measurement |
| 8 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 9 | `TIMBASIS` | CHAR | 3 |  | Time Basis |
| 10 | `TIMTYP` | CHAR | 1 |  | Time category (days or months) |
| 11 | `PREIGKL` | CHAR | 10 |  | Price adjustment clause |
| 12 | `MITTELPR` | CHAR | 1 |  | Calculation of an average price when price change occurs |
| 13 | `DPREIKZ` | CHAR | 1 |  | Average Price |
| 14 | `RUNDART` | CHAR | 1 |  | Rounding Category |
| 15 | `RUNDUNG` | CHAR | 2 |  | Starting Point for Rounding |
| 16 | `PREISART` | CHAR | 1 |  | Price type |
| 17 | `INDEXP` | CHAR | 1 |  | Index-Based Price |
| 18 | `NEXTINT` | CHAR | 1 |  | Valuate quantity portions already started using full price |
| 19 | `FRAN_TYPE` | CHAR | 1 |  | Franchise Fee Category |
| 20 | `EXTPRICE` | CHAR | 1 |  | External Price |
| 21 | `PRCZONAJ` | CHAR | 1 |  | Type of Price Block Adjustment |
| 22 | `PRCZOMIN` | NUMC | 3 |  | Lower limit of interval for price block adjustment in days |
| 23 | `PRCZOMAX` | NUMC | 3 |  | Upper limit of interval for price block adjustment in days |
| 24 | `KA_GRENZPREIS` | CHAR | 1 |  | Price Limit in Franchise Fee |
| 25 | `GROSSPRICE` | CHAR | 1 |  | Gross Price |
| 26 | `PRICEORIGIN` | CHAR | 3 |  | Price Origin |
| 27 | `ANLAGE` | CHAR | 10 |  | Installation |
| 28 | `RABART` | CHAR | 1 |  | Discount type |
| 29 | `RABTYP` | CHAR | 1 |  | Discount category |
| 30 | `HISTORY_TAB` | TTYP | 0 |  | Historical Prices for Excel Upload |
| 31 | `REF_PRICE` | REF | 0 |  | Prices |
| 32 | `MOVE_START_DATE_POSSIBLE` | CHAR | 1 |  | Character Field Length 1 |
