# ZISCSWISTEXT
**Description:** WIS Text field Table
**Total Fields:** 7
**Key Fields:** MANDT, AUFNR, TEXT_ID

## Programs Using This Table
- `ziscs0237`
- `zreprjt00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `TEXT_ID` | CHAR | 2 | 🔑 | WIS Text ID |
| 4 | `TEXT` | CHAR | 255 |  | WIS Text Content |
| 5 | `UPDATE_DATE` | DATS | 8 |  | Field of type DATS |
| 6 | `UPDATE_TIME` | TIMS | 6 |  | Time |
| 7 | `UPDATE_BY` | CHAR | 12 |  | Last Changed By |
