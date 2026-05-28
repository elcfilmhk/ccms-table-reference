# ZISBI_BRAILLEADR
**Description:** Braille address table
**Total Fields:** 11
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbi0215`
- `zisbi0217`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CUST_NAME` | CHAR | 50 |  | Braille Customer Name |
| 4 | `ADDRESS1` | CHAR | 70 |  | Braille Address line |
| 5 | `ADDRESS2` | CHAR | 70 |  | Braille Address line |
| 6 | `ADDRESS3` | CHAR | 70 |  | Braille Address line |
| 7 | `ADDRESS4` | CHAR | 70 |  | Braille Address line |
| 8 | `ADDRESS5` | CHAR | 70 |  | Braille Address line |
| 9 | `ADDRESS6` | CHAR | 70 |  | Braille Address line |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ACTIVE` | CHAR | 1 |  | Active indicator (X or blank) |
