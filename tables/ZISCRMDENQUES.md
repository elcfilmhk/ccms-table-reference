# ZISCRMDENQUES
**Description:** Data Enrichment - Survey Question
**Total Fields:** 12
**Key Fields:** MANDT, TRADE_CLASS, QUESTION_NO

## Programs Using This Table
- `ziscrm0006`
- `ziscrm0007`
- `ziscrm0008`
- `ziscs0214`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRADE_CLASS` | CHAR | 4 | 🔑 | Account class |
| 3 | `QUESTION_NO` | NUMC | 3 | 🔑 | Question number |
| 4 | `QUESTION` | CHAR | 35 |  | Question Heading |
| 5 | `ITEM1` | NUMC | 3 |  | Item no in column 1 |
| 6 | `KEY1` | CHAR | 1 |  | ID in result set? |
| 7 | `ITEM2` | NUMC | 3 |  | Item no in column 2 |
| 8 | `KEY2` | CHAR | 1 |  | ID in result set? |
| 9 | `ITEM3` | NUMC | 3 |  | Item no in column 3 |
| 10 | `KEY3` | CHAR | 1 |  | ID in result set? |
| 11 | `MULTI` | CHAR | 1 |  | Support Multi Lines - dynamic grid created in screen if yes |
| 12 | `ACTIVE` | CHAR | 1 |  | Active Flag |
