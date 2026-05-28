# ZBAPIBUS20001_TEXT_INS
**Description:** BO BusProcessND: Process Texts of a Business Transaction
**Total Fields:** 11
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0111`
- `ziscs0119`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `REF_GUID` | CHAR | 32 |  | Globally Unique Identifier in 32-Character Display |
| 2 | `REF_HANDLE` | NUMC | 10 |  | Handle |
| 3 | `REF_KIND` | CHAR | 1 |  | Object Type |
| 4 | `TDID` | CHAR | 4 |  | Text ID |
| 5 | `TDSPRAS` | LANG | 1 |  | Language Key |
| 6 | `LANGU_ISO` | CHAR | 2 |  | Language according to ISO 639 |
| 7 | `TDSTYLE` | CHAR | 8 |  | Style Name |
| 8 | `TDFORM` | CHAR | 16 |  | Form name |
| 9 | `TDFORMAT` | CHAR | 2 |  | Tag column |
| 10 | `TDLINE` | CHAR | 132 |  | Text line |
| 11 | `MODE` | CHAR | 1 |  | Processing Mode of Transaction |
