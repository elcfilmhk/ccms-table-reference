# ZISCS_AZURE_ETAG
**Description:** Etag from Azure for application
**Total Fields:** 10
**Key Fields:** MANDT, APPLN_REF, SEQUENCE

## Programs Using This Table
- `ziscs0729`
- `ziscs1120`
- `ziscspc_azure_download========ft`
- `ziscspc_azure_etag_update=====ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `APPLN_REF` | CHAR | 10 | 🔑 | Application Reference Number |
| 3 | `SEQUENCE` | NUMC | 3 | 🔑 | Sequence of the ETag created for the Application |
| 4 | `ETAG_AZURE` | CHAR | 256 |  | Etag for Azure Storage |
| 5 | `FILENAME` | CHAR | 256 |  | Text, 256 Characters |
| 6 | `DEL_IND` | CHAR | 1 |  | Single-Character Flag |
| 7 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 8 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 9 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 10 | `AEDAT` | DATS | 8 |  | Date of Last Change |
