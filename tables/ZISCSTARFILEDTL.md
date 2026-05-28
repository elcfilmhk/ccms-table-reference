# ZISCSTARFILEDTL
**Description:** CEP: Config table of the output file detail
**Total Fields:** 11
**Key Fields:** MANDT, SOURCEFROM, SOURCENAME, FIELDNAME

## Programs Using This Table
- `ziscs0444`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SOURCEFROM` | CHAR | 10 | 🔑 | Data Source Identifier |
| 3 | `SOURCENAME` | CHAR | 100 | 🔑 | File name or Table name |
| 4 | `FIELDNAME` | CHAR | 40 | 🔑 | Field name |
| 5 | `FIELDLENGTH` | NUMC | 4 |  | Number of characters of the field in the source file |
| 6 | `FIELDSEQ` | NUMC | 3 |  | Field Sequence |
| 7 | `FIELDDATATYPE` | CHAR | 1 |  | Field Data Type |
| 8 | `CRITERIA_OPTION` | CHAR | 2 |  | Option for filtering |
| 9 | `CRITERIA_SIGN` | CHAR | 1 |  | Sign for filtering (I: Include, E: Exclude) |
| 10 | `LOW` | CHAR | 100 |  | Criteria value (Low) |
| 11 | `HIGH` | CHAR | 100 |  | Criteria value (High) |
