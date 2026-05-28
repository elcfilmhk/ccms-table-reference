# ZISCSBAPI4_EXPSTR
**Description:** Export structure for retreve ESERVICE CONTACT
**Total Fields:** 13
**Key Fields:** _none_

## Programs Using This Table
- `z_bapi_retrieve_eservice_cont=ft`
- `ziscs0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CHANNEL` | CHAR | 1 |  | Dispatch |
| 2 | `ITEM` | CHAR | 10 |  | Item Number for Contact Number |
| 3 | `ATTRIBUTE1` | CHAR | 50 |  | Attribute 1 for Contact Information |
| 4 | `ATTRIBUTE2` | CHAR | 50 |  | Attribute 2 for Contact Information |
| 5 | `ATTRIBUTE3` | CHAR | 50 |  | Attribute 3 for Contact Information |
| 6 | `ATTRIBUTE4` | CHAR | 50 |  | Attribute 4 for Contact Information |
| 7 | `ATTRIBUTE5` | CHAR | 50 |  | Attribute 5 for Contact Information |
| 8 | `STANDARD` | CHAR | 1 |  | Standard |
| 9 | `STATUS` | CHAR | 1 |  | Status |
| 10 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `ERNAM` | CHAR | 12 |  | Create By |
| 12 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 13 | `AENAM` | CHAR | 12 |  | Change By |
