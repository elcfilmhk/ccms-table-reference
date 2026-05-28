# ZISCSEEC_CAATTRH
**Description:** EE&C CA attributes(full hist;ZISCSEEC_CAATTR:latest only)
**Total Fields:** 11
**Key Fields:** MANDT, VKONT, ATTR_NAME, EFF_FM_DT

## Programs Using This Table
- `ziscs0397_eec`
- `ziscs0476_eec`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ATTR_NAME` | CHAR | 30 | 🔑 | Name of CA Attribute |
| 4 | `EFF_FM_DT` | CHAR | 14 | 🔑 | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 5 | `EFF_EXP_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 6 | `ATTR_VALUE_LO` | CHAR | 100 |  | Attribute Value |
| 7 | `ATTR_VALUE_HI` | CHAR | 100 |  | Attribute Value |
| 8 | `CREATE_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 9 | `CREATE_USER` | CHAR | 12 |  | Name of Person Who Created the Object |
| 10 | `CHANGED_DT` | CHAR | 14 |  | DateTime 14 digits [Format: YYYYMMDDhhmmss] |
| 11 | `CHANGED_USER` | CHAR | 12 |  | Name of person who changed object |
