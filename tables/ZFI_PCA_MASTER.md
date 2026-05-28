# ZFI_PCA_MASTER
**Description:** Payment Card Master: General Data (Backup and Restore)
**Total Fields:** 15
**Key Fields:** CLIENT, LAUFD, .INCLUDE, CARD_GUID

## Programs Using This Table
- `zisfi0290`
- `zisfi0291`
- `zisfi0292`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `LAUFD` | DATS | 8 | 🔑 | Date ID |
| 3 | `.INCLUDE` | &nbsp; | 0 | 🔑 | Key Fields Card Master |
| 4 | `CARD_GUID` | RAW | 16 | 🔑 | GUID of a Payment Card |
| 5 | `.INCLUDE` | &nbsp; | 0 |  | Data Part Central Card Master |
| 6 | `VALID_TO` | DEC | 15 |  | Date Valid to: UTC Time Stamp in Short Form YYYYMMDDhhmmss |
| 7 | `VALID_FROM` | DEC | 15 |  | Date Valid from: UTC Time Stamp in Short Form YYYYMMDDhhmmss |
| 8 | `CARD_TYPE` | CHAR | 4 |  | Payment card type |
| 9 | `MASK_NUMBER` | CHAR | 25 |  | Masked Payment Card Number |
| 10 | `STAMP_NAME` | CHAR | 40 |  | Payment cards: Name of cardholder |
| 11 | `ISSUER` | CHAR | 40 |  | Payment cards: Issuing bank |
| 12 | `ISSUING_DATE` | DEC | 15 |  | Issue Date: UTC Time Stamp in Short Form YYYYMMDDhhmmss |
| 13 | `BACKUP_ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `BACKUP_ERZET` | TIMS | 6 |  | Entry time |
| 15 | `BACKUP_ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
