# ZDBERCHZ1
**Description:** Copy of Individual line items
**Total Fields:** 108
**Key Fields:** MANDT, BELNR, BELZEILE

## Programs Using This Table
- `zisbi0214`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 3 | `BELZEILE` | NUMC | 6 | 🔑 | Billing line item for billing documents |
| 4 | `.INCLUDE` | &nbsp; | 0 |  | Substructure of document line items: Always filled data |
| 5 | `CSNO` | NUMC | 6 |  | Sequence number of schema step during billing |
| 6 | `BELZART` | CHAR | 6 |  | Line Item Type |
| 7 | `ABSLKZ` | CHAR | 1 |  | Billing Line Item for Budget Billing Amount Determination |
| 8 | `DIFFKZ` | CHAR | 1 |  | Indicator: difference line item for discount statistics |
| 9 | `BUCHREL` | CHAR | 1 |  | Billing Line Item Relevant to Posting |
| 10 | `MENGESTREL` | CHAR | 1 |  | Quantity (billed value) is statistically relevant |
| 11 | `BETRSTREL` | CHAR | 1 |  | Amount of billing line item is statistically relevant |
| 12 | `STGRQNT` | CHAR | 6 |  | Quantity statistics group |
| 13 | `STGRAMT` | CHAR | 6 |  | Amount statistics group |
| 14 | `PRINTREL` | CHAR | 1 |  | Billing Line Is Print-Relevant |
| 15 | `AKLASSE` | CHAR | 4 |  | Billing class |
| 16 | `BRANCHE` | CHAR | 10 |  | Industry |
| 17 | `TVORG` | CHAR | 4 |  | Subtransaction for Document Item |
| 18 | `GEGEN_TVORG` | CHAR | 4 |  | Offsetting trans. for sub-transaction of billing line item |
| 19 | `TAX_TVORG` | CHAR | 4 |  | Subtransaction for tax determination for BB line items |
| 20 | `LINESORT` | CHAR | 4 |  | Presorting of billing line items in billing schema |
| 21 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 22 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 23 | `TIMTYPZA` | CHAR | 1 |  | Time category (days or months) for billing line item |
| 24 | `SCHEMANR` | CHAR | 10 |  | Number of the billing schema |
| 25 | `SNO` | NUMC | 4 |  | Sequence number of schema step in billing schema |
| 26 | `PROGRAMM` | CHAR | 8 |  | Variant program |
| 27 | `MASSBILL` | UNIT | 3 |  | Unit of measurement for billing |
| 28 | `SAISON` | CHAR | 10 |  | Season |
| 29 | `TIMBASIS` | CHAR | 3 |  | Time Basis |
| 30 | `TIMTYP` | CHAR | 1 |  | Time category (days or months) |
| 31 | `FRAN_TYPE` | CHAR | 1 |  | Franchise Fee Category |
| 32 | `KONZIGR` | CHAR | 10 |  | Franchise fee group |
| 33 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 34 | `TARIFNR` | CHAR | 10 |  | Rate key |
| 35 | `KONDIGR` | CHAR | 10 |  | Rate fact group |
| 36 | `STTARIF` | CHAR | 10 |  | Statistical rate |
| 37 | `GEWKEY` | CHAR | 8 |  | Weighting key |
| 38 | `WDHFAKT` | INT4 | 10 |  | Repetition factor for reference values |
| 39 | `TEMP_AREA` | CHAR | 8 |  | Temperature area |
| 40 | `DRCKSTUF` | CHAR | 2 |  | Gas pressure level |
| 41 | `ABGGRND1` | CHAR | 4 |  | Reason for proration |
| 42 | `ABGGRND2` | CHAR | 4 |  | Reason for proration |
| 43 | `ABGGRND3` | CHAR | 4 |  | Reason for proration |
| 44 | `ABGGRND4` | CHAR | 4 |  | Reason for proration |
| 45 | `ABGGRND5` | CHAR | 4 |  | Reason for proration |
| 46 | `ABGGRND6` | CHAR | 4 |  | Reason for proration |
| 47 | `ABGGRND7` | CHAR | 4 |  | Reason for proration |
| 48 | `ABGGRND8` | CHAR | 4 |  | Reason for proration |
| 49 | `ABGGRND9` | CHAR | 4 |  | Reason for proration |
| 50 | `ABGGRND10` | CHAR | 4 |  | Reason for proration |
| 51 | `EIN01` | CHAR | 10 |  | Input operand |
| 52 | `EIN02` | CHAR | 10 |  | Input operand |
| 53 | `EIN03` | CHAR | 10 |  | Input operand |
| 54 | `EIN04` | CHAR | 10 |  | Input operand |
| 55 | `AUS01` | CHAR | 10 |  | Output operand |
| 56 | `AUS02` | CHAR | 10 |  | Output operand |
| 57 | `MASS1` | UNIT | 3 |  | Unit of Measurement |
| 58 | `MASS2` | UNIT | 3 |  | Unit of Measurement |
| 59 | `MASS3` | UNIT | 3 |  | Unit of Measurement |
| 60 | `MASS4` | UNIT | 3 |  | Unit of Measurement |
| 61 | `DATUM1` | DATS | 8 |  | Date |
| 62 | `DATUM2` | DATS | 8 |  | Date |
| 63 | `RABZUS` | CHAR | 10 |  | Discount key |
| 64 | `BACKCANC01` | CHAR | 4 |  | Indicator: reverse backbilling |
| 65 | `BACKCANC02` | CHAR | 4 |  | Indicator: reverse backbilling |
| 66 | `BACKCANC03` | CHAR | 4 |  | Indicator: reverse backbilling |
| 67 | `BACKCANC04` | CHAR | 4 |  | Indicator: reverse backbilling |
| 68 | `BACKCANC05` | CHAR | 4 |  | Indicator: reverse backbilling |
| 69 | `BACKCANC` | CHAR | 4 |  | Indicator: Reverse Backbilling |
| 70 | `BACKEXEC` | CHAR | 4 |  | Indicator: allocate backbilling |
| 71 | `BACKDOCNO` | CHAR | 12 |  | Number of a billing document |
| 72 | `BACKDOCLINE` | NUMC | 6 |  | Billing line item for billing documents |
| 73 | `DYNCANC01` | CHAR | 4 |  | Schema steps for reversal in dynamic period control 1 |
| 74 | `DYNCANC02` | CHAR | 4 |  | Reversal indicator, dynamic period control 2 |
| 75 | `DYNCANC03` | CHAR | 4 |  | Reversal indicator, dynamic period control 3 |
| 76 | `DYNCANC04` | CHAR | 4 |  | Reversal Indicator, Dynamic Period Control 4 |
| 77 | `DYNCANC05` | CHAR | 4 |  | Reversal indicator, dynamic period control 5 |
| 78 | `DYNCANC` | CHAR | 4 |  | Indicator: Reverse Backbilling |
| 79 | `DYNEXEC` | CHAR | 4 |  | Indicator: Allocate Backbilling |
| 80 | `LRATESTEP` | NUMC | 10 |  | Logical Number of Rate Step |
| 81 | `PEB` | CHAR | 1 |  | Indicator: billing line item relates to period-end billing |
| 82 | `OPLFDNR` | NUMC | 4 |  | Consecutive number of an operand |
| 83 | `STAFO` | CHAR | 6 |  | Update group for statistics update |
| 84 | `ARTMENGE` | CHAR | 1 |  | Classification of billed quantity for statistics |
| 85 | `STATTART` | CHAR | 8 |  | Rate type for statistical analysis |
| 86 | `TIMECONTRL` | CHAR | 2 |  | Period control |
| 87 | `TCNUMTOR` | DEC | 8 |  | Numerator of the time portion in a time slice |
| 88 | `TCDENOMTOR` | DEC | 8 |  | Denominator of the time portion in a time slice |
| 89 | `TIMTYPQUOT` | CHAR | 1 |  | Time category of meter for time portion of a time slice |
| 90 | `AKTIV` | CHAR | 1 |  | Meter reading active |
| 91 | `KONZVER` | CHAR | 10 |  | Franchise contract |
| 92 | `PERTYP` | CHAR | 2 |  | Category of the internal billing period |
| 93 | `ERCHV_ANCHOR` | CHAR | 1 |  | Anchor Line for DBERCHV Entry |
| 94 | `OUCONTRACT` | CHAR | 10 |  | Master Agreement for Individual Contract |
| 95 | `.INCLUDE` | &nbsp; | 0 |  | &nbsp; |
| 96 | `.INCLUDE` | &nbsp; | 0 |  | Pre-/decimal places of always filled ERCHZ fields |
| 97 | `V_ABRMENGE` | DEC | 17 |  | Places before decimal point in billing quantity |
| 98 | `N_ABRMENGE` | DEC | 14 |  | Places after decimal point in billing quantity |
| 99 | `V_ZAHL1` | DEC | 17 |  | Pre-decimal places in a number |
| 100 | `N_ZAHL1` | DEC | 14 |  | Decimal places in a number |
| 101 | `V_ZAHL2` | DEC | 17 |  | Pre-decimal places in a number |
| 102 | `N_ZAHL2` | DEC | 14 |  | Decimal places in a number |
| 103 | `V_ZAHL3` | DEC | 17 |  | Pre-decimal places in a number |
| 104 | `N_ZAHL3` | DEC | 14 |  | Decimal places in a number |
| 105 | `V_ZAHL4` | DEC | 17 |  | Pre-decimal places in a number |
| 106 | `N_ZAHL4` | DEC | 14 |  | Decimal places in a number |
| 107 | `V_ZEITANT` | DEC | 17 |  | Predecimal place of a time portion |
| 108 | `N_ZEITANT` | DEC | 14 |  | Decimal places of a time portion |
