# ZISDMMRECS
**Description:** Custom table to handle M Records of Meter Reading Upload
**Total Fields:** 29
**Key Fields:** MANDT, PID, OWNID, REFID

## Programs Using This Table
- `zisdh0004`
- `zisdh0020`
- `zisdh0024`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0103`
- `zisdm0142`
- `zisdm0143`
- `zisdm0156`
- `zisdm0407`
- `zisdm0409`
- `zisdm0411`
- `zrdm_dr_rep`
- `zrdm_us_rep`
- `zrdm_wd_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PID` | NUMC | 5 | 🔑 | Process ID |
| 3 | `OWNID` | CHAR | 10 | 🔑 | Own Identification |
| 4 | `REFID` | CHAR | 10 | 🔑 | Reference Identification |
| 5 | `RECORDID` | CHAR | 2 |  | Record ID |
| 6 | `METERNUMBER` | CHAR | 18 |  | Serial Number |
| 7 | `METERTYPE` | CHAR | 1 |  | Changed Note Indicator |
| 8 | `METERSTATUS` | CHAR | 1 |  | Changed Note Indicator |
| 9 | `JOBTYPE` | CHAR | 14 |  | Meter Number |
| 10 | `EMPLOYEEID` | CHAR | 8 |  | User ID |
| 11 | `HANDHELDID` | CHAR | 1 |  | Basic device category |
| 12 | `ACTUALMRDATE` | DATS | 8 |  | Date |
| 13 | `ACTUALMRTIME` | TIMS | 6 |  | Time |
| 14 | `ELAPSEDTIME` | NUMC | 5 |  | Elapsed time in seconds |
| 15 | `ZZJOBSTAT` | CHAR | 2 |  | Job Status of meter reading action |
| 16 | `READCODE` | NUMC | 2 |  | Cant' Read Code |
| 17 | `CMNTCODE1` | NUMC | 2 |  | Comment Code |
| 18 | `CMNTCODE2` | NUMC | 2 |  | Comment Code |
| 19 | `CMNTCODE3` | NUMC | 2 |  | Comment Code |
| 20 | `CMNTCODE4` | NUMC | 2 |  | Comment Code |
| 21 | `CMNTCODE5` | NUMC | 2 |  | Comment Code |
| 22 | `COMMENTS` | CHAR | 80 |  | Note Text |
| 23 | `SEQUENCECHANGE` | CHAR | 1 |  | Change Sequence |
| 24 | `NEWSEQUENCE` | NUMC | 8 |  | Reference node for start of a sequence |
| 25 | `SEALCHANGE` | CHAR | 1 |  | Indicator: Data was changed |
| 26 | `NEWSEAL` | CHAR | 12 |  | Indicator: changed with new effectivity |
| 27 | `NEARESTMETER` | CHAR | 14 |  | Meter Number |
| 28 | `.INCLUDE` | &nbsp; | 0 |  | Additional Data |
| 29 | `SOURCE_SYSTEM` | CHAR | 1 |  | Source System |
