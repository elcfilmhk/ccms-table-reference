# ZEDMISUPROVAL_FILE_AMI01
**Description:** Structure for Uploading Profile Values from a File
**Total Fields:** 10
**Key Fields:** _none_

## Programs Using This Table
- `zised0057`
- `zised0058`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `SERNR` | CHAR | 18 |  | Serial Number |
| 2 | `UNIT` | CHAR | 10 |  | Unit of measurement of profile value in general interface |
| 3 | `DATEFROM` | DATS | 8 |  | From-Date |
| 4 | `TIMEFROM` | TIMS | 6 |  | From-time |
| 5 | `FROMOFFSET` | CHAR | 3 |  | Offset for time difference |
| 6 | `DATETO` | DATS | 8 |  | To-Date |
| 7 | `TIMETO` | TIMS | 6 |  | To-Time |
| 8 | `TOOFFSET` | CHAR | 3 |  | Offset for time difference |
| 9 | `VALUE` | CHAR | 31 |  | Profile value in interface |
| 10 | `STATUS` | CHAR | 4 |  | Status of profile value in interface |
