# ZISCS_EEC_CA_ATTR_LIST
**Description:** List of CA Attributes
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0386_eec`
- `ziscs0398_eec`
- `ziscseec_get_ca_attr==========ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `.INCLUDE` | &nbsp; | 0 |  | EE&C CA attributes(latest only;ZISCSEEC_CAATTRH: full hist.) |
| 2 | `MANDT` | CLNT | 3 |  | Client |
| 3 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 4 | `ATTR_NAME` | CHAR | 30 |  | Name of CA Attribute |
| 5 | `EFF_FM_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 7 | `ATTR_VALUE_LO` | CHAR | 100 |  | Attribute Value |
| 8 | `ATTR_VALUE_HI` | CHAR | 100 |  | Attribute Value |
| 9 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 10 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 11 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 12 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
| 13 | `ATTR_CATEGORY` | CHAR | 50 |  | CA Attribute Category |
| 14 | `DEL_FLAG` | CHAR | 1 |  | Single-Character Flag |
