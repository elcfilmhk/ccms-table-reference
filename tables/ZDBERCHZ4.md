# ZDBERCHZ4
**Description:** Copy of Individual line items (rarely used fields)
**Total Fields:** 58
**Key Fields:** MANDT, BELNR, BELZEILE

## Programs Using This Table
- `zisbi0214`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `BELZEILE` | NUMC | 6 | 🔑 | Billing line item for billing documents |
| 4 | `.INCLUDE` | &nbsp; | 0 |  | Substructure of document line items, rarely used fields |
| 5 | `LEUCHTNR` | CHAR | 10 |  | External lighting number |
| 6 | `BETRART` | CHAR | 4 |  | Operation Type for Lighting Unit |
| 7 | `SPGRUND` | CHAR | 2 |  | Disconnection reason |
| 8 | `EIN05` | CHAR | 10 |  | Input operand |
| 9 | `EIN06` | CHAR | 10 |  | Input operand |
| 10 | `EIN07` | CHAR | 10 |  | Input operand |
| 11 | `EIN08` | CHAR | 10 |  | Input operand |
| 12 | `EIN09` | CHAR | 10 |  | Input operand |
| 13 | `EIN10` | CHAR | 10 |  | Input operand |
| 14 | `AUS03` | CHAR | 10 |  | Output operand |
| 15 | `AUS04` | CHAR | 10 |  | Output operand |
| 16 | `AUS05` | CHAR | 10 |  | Output operand |
| 17 | `MASS5` | UNIT | 3 |  | Unit of Measurement |
| 18 | `MASS6` | UNIT | 3 |  | Unit of Measurement |
| 19 | `SC_BELNR` | CHAR | 12 |  | Number of billing document in adjustment reversal |
| 20 | `SC_BELZEILE` | NUMC | 6 |  | Billing line item for billing documents |
| 21 | `REFBELZEILE` | NUMC | 6 |  | Reference billing line item for billing documents |
| 22 | `SPERRUNG` | CHAR | 1 |  | Time slice is in a disconnection period |
| 23 | `NETTOFRMD` | CURR | 13 |  | Amount in foreign currency with +/- sign |
| 24 | `WAERSF` | CUKY | 5 |  | Currency key for amount |
| 25 | `UMRECHDAT` | DATS | 8 |  | Conversion Date for Foreign Currency Amount |
| 26 | `UMRECHKURS` | DEC | 9 |  | Exchange rate btwn net amount and foreign currency amount |
| 27 | `REFBELZONE` | NUMC | 6 |  | Ref. billing line item for documents resulting from blocking |
| 28 | `REFBILLDOCNO` | CHAR | 12 |  | Reference Document Number |
| 29 | `FIRSTBELNR` | CHAR | 12 |  | Billing Document Number of First Invoiced Document |
| 30 | `TAXREL` | CHAR | 1 |  | Line Contains Tax Determination Quantity for Invoicing |
| 31 | `TAXGROUP` | CHAR | 4 |  | Categorize Amounts for Tax Determination |
| 32 | `BILLTYPE` | CHAR | 6 |  | Waste Billing Category |
| 33 | `OBJNR` | CHAR | 10 |  | Number of service frequency |
| 34 | `ORDERNR` | CHAR | 20 |  | Internal Number for Identifying a Waste Disposal Order |
| 35 | `LAUFNR` | NUMC | 5 |  | Sequence Number of Service Frequency |
| 36 | `ORDER_LAUFNR` | NUMC | 4 |  | Sequence Number for Waste Disposal Order Item |
| 37 | `GGVERTRAG` | CHAR | 18 |  | Guarantor Contract |
| 38 | `OLD_BELNR` | CHAR | 12 |  | Number of a billing document |
| 39 | `CONDIREF` | NUMC | 4 |  | Internal: Reference Number for a Condition |
| 40 | `DATEFROM` | DATS | 8 |  | Start Date |
| 41 | `TIMEFROM` | TIMS | 6 |  | Start Time |
| 42 | `DATETO` | DATS | 8 |  | End Date |
| 43 | `TIMETO` | TIMS | 6 |  | End Time |
| 44 | `RATERELGROUP` | CHAR | 10 |  | Rate Relationship Group (in Schema) |
| 45 | `BASIC_RATE` | CHAR | 10 |  | Rate key |
| 46 | `RATERELCAT` | NUMC | 1 |  | Rate Relationship Category |
| 47 | `CONDBILLPROGID` | CHAR | 10 |  | Conditional Billing Program ID |
| 48 | `GEN_CONTRACT` | CHAR | 10 |  | Contract |
| 49 | `REC_CONTRACT` | CHAR | 10 |  | Contract |
| 50 | `GEN_TOU` | CHAR | 5 |  | Generating TOU |
| 51 | `REC_TOU` | CHAR | 5 |  | ISU_Brazil: Consuming TOU |
| 52 | `PROPORTION` | DEC | 5 |  | &nbsp; |
| 53 | `PROPORTION_EXT` | DEC | 8 |  | Distribution Proportion |
| 54 | `.INCLUDE` | &nbsp; | 0 |  | Pre-/decimal places in rarely used ERCHZ fields |
| 55 | `V_ZAHL5` | DEC | 17 |  | Pre-decimal places in a number |
| 56 | `N_ZAHL5` | DEC | 14 |  | Decimal places in a number |
| 57 | `V_ZAHL6` | DEC | 17 |  | Pre-decimal places in a number |
| 58 | `N_ZAHL6` | DEC | 14 |  | Decimal places in a number |
