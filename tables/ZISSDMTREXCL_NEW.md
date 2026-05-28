# ZISSDMTREXCL_NEW
**Description:** Meter Exclusion Table
**Total Fields:** 11
**Key Fields:** MANDT, VBELN, METER, VSTELLE, MATNR

## Programs Using This Table
- `zissd00104`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VBELN` | CHAR | 10 | 🔑 | Sales Document |
| 3 | `METER` | CHAR | 18 | 🔑 | Meter Number |
| 4 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 5 | `MATNR` | CHAR | 18 | 🔑 | Material Number |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERTIM` | TIMS | 6 |  | Create time |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 9 | `DLDAT` | DATS | 8 |  | Delete Date |
| 10 | `DLTIM` | TIMS | 6 |  | Delete time |
| 11 | `DLNAM` | CHAR | 12 |  | Deletion: User |
