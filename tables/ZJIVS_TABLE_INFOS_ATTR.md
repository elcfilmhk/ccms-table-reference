# ZJIVS_TABLE_INFOS_ATTR
**Description:** JiVS structure for tableinfos / metadata
**Total Fields:** 5
**Key Fields:** _none_

## Programs Using This Table
- `zjivs_export`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `TABNAME` | CHAR | 30 |  | Table Name |
| 2 | `TABLETYPE` | CHAR | 8 |  | Table Category |
| 3 | `CLIENT_SPECIFIC` | CHAR | 1 |  | JIVS Data element for client specific mark |
| 4 | `CLIENT_SPECIFIC_TXT` | CHAR | 255 |  | JiVS client specific text |
| 5 | `CLIENT_FIELD` | CHAR | 1 |  | General Flag |
