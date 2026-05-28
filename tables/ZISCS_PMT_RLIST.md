# ZISCS_PMT_RLIST
**Description:** Payment Ranking List
**Total Fields:** 24
**Key Fields:** MANDT, BEN_ID, PROG_ID, NGO_CODE, APPLN_REF

## Programs Using This Table
- `z_iscspc_subsidy_lock_fail====ft`
- `ziscs0815`
- `ziscs0815_01`
- `ziscs0817`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BEN_ID` | CHAR | 2 | 🔑 | Beneficiary ID |
| 3 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 4 | `NGO_CODE` | CHAR | 8 | 🔑 | Branch Code |
| 5 | `APPLN_REF` | CHAR | 10 | 🔑 | Application Reference Number |
| 6 | `APPLN_DT` | DATS | 8 |  | Application Date |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `RANK` | NUMC | 8 |  | RANK |
| 9 | `PRIORITY_S` | CHAR | 1 |  | Priority Selection |
| 10 | `APPLN_S` | CHAR | 1 |  | Application Selected |
| 11 | `AMOUNT` | CURR | 9 |  | Payment Amount |
| 12 | `CURR` | CUKY | 5 |  | SD Document Currency |
| 13 | `SUBMITTED_BY` | CHAR | 12 |  | Submitted By |
| 14 | `SUBMITTED_ON` | DATS | 8 |  | Submitted On |
| 15 | `APPROVED_BY` | CHAR | 12 |  | Approved By |
| 16 | `APPROVED_ON` | DATS | 8 |  | Approved On |
| 17 | `REJECTED_BY` | CHAR | 12 |  | Rejected By |
| 18 | `REJECTED_ON` | DATS | 8 |  | Rejected On |
| 19 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 20 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 21 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 22 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 23 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 24 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
