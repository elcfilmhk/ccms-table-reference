# ZBAPIBUS2000110_HEADER_INS
**Description:** BO Activity CRM: Header Data CRM Activity in Change Mode
**Total Fields:** 27
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
| 13 | `CATEGORY` | CHAR | 3 |  | Category of an Activity (Communication Type) |
| 14 | `PRIORITY` | NUMC | 1 |  | Activity Priority |
| 15 | `OBJECTIVE` | CHAR | 3 |  | Goal of an Activity |
| 16 | `DIRECTION` | CHAR | 1 |  | Direction of an Activity |
| 17 | `EXTERN_ACT_ID` | CHAR | 20 |  | External Business Transaction Number |
| 18 | `ADDRESS_ID` | CHAR | 10 |  | Location where Activity takes place |
| 19 | `ADDRESS_GUID` | CHAR | 32 |  | GUID for an Address Object in BAPI Format |
| 20 | `PRIVATE_FLAG` | CHAR | 1 |  | Indicator: Task is Private |
| 21 | `COMPLETION` | NUMC | 3 |  | Completion Rate in Percent |
| 22 | `POSTING_DATE` | DATS | 8 |  | Posting Date for a Business Transaction |
| 23 | `MODE` | CHAR | 1 |  | Processing Mode of Transaction |
| 24 | `CREATED_AT` | DEC | 15 |  | Transaction was Created at this Time |
| 25 | `CREATED_BY` | CHAR | 12 |  | User that Created the Transaction |
| 26 | `CHANGED_AT` | DEC | 15 |  | Time of Last Change to the Transaction |
| 27 | `CHANGED_BY` | CHAR | 12 |  | Transaction Last Changed By |
