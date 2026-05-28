# ZISCS_SERV_ORD_INFO
**Description:** ISU Service Order Info.
**Total Fields:** 14
**Key Fields:** _none_

## Programs Using This Table
- `zcl_isu_serv_ord_util`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `REQUIRED` | CHAR | 1 |  | Logical Variable |
| 2 | `OPERATION` | CHAR | 1 |  | mode for month week day |
| 3 | `OBJECT_TYPE` | CHAR | 20 |  | UI Object Type |
| 4 | `SERV_ORD_TYPE` | CHAR | 4 |  | Not More Closely Defined Area, Possibly Used for Patchlevels |
| 5 | `SERV_ORD_NO` | CHAR | 12 |  | Character Field of Length 12 |
| 6 | `PMACTTYPE` | CHAR | 35 |  | Data Element Type CHAR Length 35 |
| 7 | `CONTACT_PERSON` | CHAR | 40 |  | Character field of length 40 |
| 8 | `CONTACT_NO` | CHAR | 8 |  | Character field, 8 characters long |
| 9 | `LOADING_INFO` | CHAR | 40 |  | Character field of length 40 |
| 10 | `PREMISE` | CHAR | 10 |  | Character Field Length = 10 |
| 11 | `INSTALLATION` | CHAR | 10 |  | Character Field Length = 10 |
| 12 | `CANCEL_ZMR_REQD` | CHAR | 1 |  | Logical Variable |
| 13 | `CANCEL_ZDM_REQD` | CHAR | 1 |  | Logical Variable |
| 14 | `CANCEL_ZRC_REQD` | CHAR | 1 |  | Logical Variable |
