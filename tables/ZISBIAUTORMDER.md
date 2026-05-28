# ZISBIAUTORMDER
**Description:** Autopay reminder information for SMS/Email
**Total Fields:** 13
**Key Fields:** MANDT, ERDAT, VKONT, DELTYP

## Programs Using This Table
- `zisbi0043`
- `zisbi0043n`
- `zisbi0092`
- `zisbi0176`
- `zisbi0179`
- `zisfi0102`
- `zisfi0110`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `DELTYP` | CHAR | 1 | 🔑 | Delivery Type for SMS/Email |
| 5 | `AUTOPAYCALL` | CHAR | 20 |  | Autopay Reminder Call number |
| 6 | `BETRW` | CURR | 13 |  | Amount in Transaction Currency with +/- Sign |
| 7 | `FAEDN` | DATS | 8 |  | Due date for net payment |
| 8 | `LANGU` | LANG | 1 |  | Language in connection with the contract account |
| 9 | `COPRI` | DATS | 8 |  | Print Date |
| 10 | `EMAIL` | CHAR | 50 |  | Correspondence email |
| 11 | `ZBNKN` | CHAR | 18 |  | Bank account number of the payee |
| 12 | `GPART` | CHAR | 12 |  | Business Partner Reference |
| 13 | `TARIFTYP` | CHAR | 10 |  | Rate category |
