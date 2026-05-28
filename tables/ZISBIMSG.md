# ZISBIMSG
**Description:** The message for a bill
**Total Fields:** 31
**Key Fields:** MANDT, MESSAGE_NO

## Programs Using This Table
- `z_isbi_billmsg_mkt_consent====ft`
- `zis_batch_insert_message======ft`
- `zis_new_batch_criteria========ft`
- `zisbi0005`
- `zisbi0010`
- `zisbi0174`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MESSAGE_NO` | NUMC | 10 | 🔑 | Message number |
| 3 | `DESCRIPTION` | CHAR | 50 |  | Description |
| 4 | `VALID_FROM` | DATS | 8 |  | Valid From Date |
| 5 | `VALID_TO` | DATS | 8 |  | Valid To Date |
| 6 | `PRIORITY` | NUMC | 6 |  | Priority |
| 7 | `COLOR1` | CHAR | 1 |  | The color of a part of a bill |
| 8 | `SIZE1` | CHAR | 1 |  | Font size for a bill |
| 9 | `EN_MESSAGE1` | CHAR | 132 |  | The bill message in english |
| 10 | `CH_MESSAGE1` | CHAR | 132 |  | The bill message in chinese |
| 11 | `COLOR2` | CHAR | 1 |  | The color of a part of a bill |
| 12 | `SIZE2` | CHAR | 1 |  | Font size for a bill |
| 13 | `EN_MESSAGE2` | CHAR | 132 |  | The bill message in english |
| 14 | `CH_MESSAGE2` | CHAR | 132 |  | The bill message in chinese |
| 15 | `COLOR3` | CHAR | 1 |  | The color of a part of a bill |
| 16 | `SIZE3` | CHAR | 1 |  | Font size for a bill |
| 17 | `EN_MESSAGE3` | CHAR | 132 |  | The bill message in english |
| 18 | `CH_MESSAGE3` | CHAR | 132 |  | The bill message in chinese |
| 19 | `COLOR4` | CHAR | 1 |  | The color of a part of a bill |
| 20 | `SIZE4` | CHAR | 1 |  | Font size for a bill |
| 21 | `EN_MESSAGE4` | CHAR | 132 |  | The bill message in english |
| 22 | `CH_MESSAGE4` | CHAR | 132 |  | The bill message in chinese |
| 23 | `EXTEND_MSG5` | CHAR | 1 |  | Extend the message |
| 24 | `COLOR5` | CHAR | 1 |  | The color of a part of a bill |
| 25 | `SIZE5` | CHAR | 1 |  | Font size for a bill |
| 26 | `EN_MESSAGE5` | CHAR | 132 |  | The bill message in english |
| 27 | `CH_MESSAGE5` | CHAR | 132 |  | The bill message in chinese |
| 28 | `COLOR6` | CHAR | 1 |  | The color for graphic logo |
| 29 | `SIZE6` | CHAR | 1 |  | Font size for a bill |
| 30 | `EN_MESSAGE6` | CHAR | 3 |  | English Logo |
| 31 | `CH_MESSAGE6` | CHAR | 3 |  | Chinese Logo |
