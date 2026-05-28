# ZISMDCONVPREM
**Description:** Premise
**Total Fields:** 15
**Key Fields:** MANDT, VSTELLE

## Programs Using This Table
- `zismd0001`
- `zismd0002`
- `zismd0010`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client ID |
| 2 | `VSTELLE` | CHAR | 10 | 🔑 | Premise |
| 3 | `HAUS` | CHAR | 30 |  | Connection Object |
| 4 | `VBSART` | CHAR | 8 |  | Type of premise |
| 5 | `STATUS` | CHAR | 15 |  | Status |
| 6 | `FLAECHE` | DEC | 9 |  | Floor Area in Square Meters |
| 7 | `REGIOGROUP` | CHAR | 8 |  | Regional structure grouping |
| 8 | `ADDRESS1` | CHAR | 200 |  | Address1 |
| 9 | `ADDRESS2` | CHAR | 200 |  | Address1 |
| 10 | `CITY` | CHAR | 40 |  | District |
| 11 | `COUNTY` | CHAR | 40 |  | City |
| 12 | `COUNTRY` | CHAR | 15 |  | Country Name |
| 13 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 14 | `REGIOGROUP_ADDR` | CHAR | 8 |  | Regional structure grouping |
| 15 | `TASKOPERATION` | CHAR | 10 |  | Task Operation |
