# ZBAPIBUS20001_HEADER_INS
**Description:** BO BusProcessND: Administration Data Trans. Header Create()
**Total Fields:** 15
**Key Fields:** _none_

## Programs Using This Table
- `ziscs0111`
- `ziscs0118`
- `ziscs0119`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `GUID` | CHAR | 32 |  | Globally Unique Identifier in 32-Character Display |
| 2 | `HANDLE` | NUMC | 10 |  | Handle |
| 3 | `PROCESS_TYPE` | CHAR | 4 |  | Business Transaction Type |
| 4 | `OBJECT_ID` | CHAR | 10 |  | Transaction Number |
| 5 | `PREDECESSOR_PROCESS` | CHAR | 70 |  | Persistent Identification of a Preceding Object |
| 6 | `PREDECESSOR_OBJECT_TYPE` | CHAR | 10 |  | Object Type for Preceding Object |
| 7 | `PREDECESSOR_LOG_SYSTEM` | CHAR | 10 |  | Logical System |
| 8 | `BIN_RELATION_TYPE` | CHAR | 4 |  | Binary Relation Type for Object Relationship Service |
| 9 | `LOGICAL_SYSTEM` | CHAR | 10 |  | Logical System |
| 10 | `DESCR_LANGUAGE` | LANG | 1 |  | Language Key of Description |
| 11 | `LANGU_ISO` | CHAR | 2 |  | Language according to ISO 639 |
| 12 | `DESCRIPTION` | CHAR | 40 |  | Transaction Description |
| 13 | `POSTING_DATE` | DATS | 8 |  | Posting Date for a Business Transaction |
| 14 | `CREATED_AT` | DEC | 15 |  | Transaction was Created at this Time |
| 15 | `CREATED_BY` | CHAR | 12 |  | User that Created the Transaction |
