# ZBW_ISU_DISCONN_DOC_TRAN
**Description:** BW Extract Structure - ISU Disconnect Documents
**Total Fields:** 21
**Key Fields:** _none_

## Programs Using This Table
- `z_bw_extract_disconn_doc======ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `EQUNR` | CHAR | 18 |  | Equipment Number |
| 2 | `SERNR` | CHAR | 18 |  | Serial Number |
| 3 | `DISCNO` | CHAR | 12 |  | Disconnection document number |
| 4 | `DISCOBJ` | NUMC | 4 |  | Disconnection object number |
| 5 | `DISCOBJTYP` | CHAR | 2 |  | Disconnection object category |
| 6 | `ANLAGE` | CHAR | 10 |  | Installation |
| 7 | `LOGIKNR` | NUMC | 18 |  | Logical device number |
| 8 | `LOGIKZW` | NUMC | 18 |  | Logical register number |
| 9 | `NEWDISCNO` | CHAR | 12 |  | Disconnection document number of subsequent disconn. documnt |
| 10 | `VACANTFLAG` | CHAR | 1 |  | Indicator: whether refer. to VSD doc. still active |
| 11 | `AMIFLAG` | CHAR | 1 |  | AMI processing flag |
| 12 | `AMITRIGGERED` | CHAR | 1 |  | Indicates an AMI Disconnection Activity |
| 13 | `REMOV_FLAG` | CHAR | 1 |  | Removal/Installation Status |
| 14 | `REPLACE_DISCOBJ` | NUMC | 4 |  | Disconnection Document: Replacment Disconnection Object |
| 15 | `BIS` | DATS | 8 |  | Date to which a disconnection is valid |
| 16 | `BIS_TIME` | TIMS | 6 |  | Time until which a disconnection is effective |
| 17 | `DISCACT_BEGIN` | NUMC | 4 |  | Disconnection activity that caused creation of period |
| 18 | `AB` | DATS | 8 |  | Date from which a disconnection is valid |
| 19 | `AB_TIME` | TIMS | 6 |  | Time from which a disconnection is effective |
| 20 | `DISCSTATE` | CHAR | 2 |  | Disconnection status |
| 21 | `DISCACT_END` | NUMC | 4 |  | Disconnection activity that caused end of period |
