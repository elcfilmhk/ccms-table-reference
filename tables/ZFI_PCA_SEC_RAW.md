# ZFI_PCA_SEC_RAW
**Description:** Card Master: Encryption (Backup and Restore)
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
| 5 | `CARD_TYPE` | CHAR | 4 |  | Payment card type |
| 6 | `CRYPTIC_NUMBER` | RSTR | 0 |  | Externally Encrypted Payment Card Number |
| 7 | `CRYPTIC_LEN` | INT4 | 10 |  | Length of Encoded Payment Card Number |
| 8 | `CRYPTIC_HASH` | CHAR | 32 |  | Hash Value of an Encrypted Payment Card Number |
| 9 | `CRYPTIC_VALUE` | CHAR | 25 |  | Payment Card Value |
| 10 | `ENCRYP_APPLI` | CHAR | 6 |  | SSF Application |
| 11 | `KEYVERSION` | INT4 | 10 |  | SSF Key Version |
| 12 | `PAREA` | NUMC | 3 |  | Subarea (for Parallel Processing) |
| 13 | `BACKUP_ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 14 | `BACKUP_ERZET` | TIMS | 6 |  | Entry time |
| 15 | `BACKUP_ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
