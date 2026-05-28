# ZISSDSALEDOCHIST
**Description:** Mass upload of Sales data captured
**Total Fields:** 11
**Key Fields:** MANDT, SALES_TYPE, APPNO, MATNR, CA, PREMISE

## Programs Using This Table
- `ziscrm0313`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SALES_TYPE` | CHAR | 3 | 🔑 | Sale Type |
| 3 | `APPNO` | CHAR | 10 | 🔑 | Application no. |
| 4 | `MATNR` | CHAR | 18 | 🔑 | Material Number |
| 5 | `CA` | CHAR | 12 | 🔑 | Contract Account Number |
| 6 | `PREMISE` | CHAR | 10 | 🔑 | Premise |
| 7 | `SPART` | CHAR | 2 |  | Division |
| 8 | `TRANSACTION_DATE` | DATS | 8 |  | Application Date |
| 9 | `KONDM` | CHAR | 2 |  | Material Pricing Group |
| 10 | `QUANTITY` | NUMC | 5 |  | Number |
| 11 | `STATUS` | CHAR | 6 |  | STATUS of mass upload of Sales data captured |
