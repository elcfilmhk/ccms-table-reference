# ZISBIINSERTCATXT
**Description:** Bill Insert contract account long text
**Total Fields:** 7
**Key Fields:** MANDT, INSERT_NO

## Programs Using This Table
- `zisbi0150`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INSERT_NO` | NUMC | 10 | 🔑 | Insert Number |
| 3 | `SHORT_TEXT` | CHAR | 70 |  | Short text |
| 4 | `LONG_TEXT_1` | CHAR | 70 |  | Long text line 1 |
| 5 | `LONG_TEXT_2` | CHAR | 70 |  | Long text line 2 |
| 6 | `LONG_TEXT_3` | CHAR | 70 |  | Long text line 3 |
| 7 | `EXPIRY_NO_MTH` | NUMC | 2 |  | Expiry after month |
