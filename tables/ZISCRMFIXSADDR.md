# ZISCRMFIXSADDR
**Description:** CRM fix supply address for MI
**Total Fields:** 8
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zaccount`
- `ziscrm0045`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 4 | `VSTELLE` | CHAR | 10 |  | Premise |
| 5 | `EINZDAT` | DATS | 8 |  | Move-In Date |
| 6 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 7 | `ERZET` | TIMS | 6 |  | Entry time |
| 8 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
