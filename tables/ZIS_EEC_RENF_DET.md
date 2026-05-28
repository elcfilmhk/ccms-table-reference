# ZIS_EEC_RENF_DET
**Description:** RE Application - Location Mapping
**Total Fields:** 21
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0838`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `REINF_AUFNR` | CHAR | 12 |  | Order Number |
| 4 | `PL_USERID` | CHAR | 12 |  | User Name in User Master Record |
| 5 | `SE_USERID` | CHAR | 12 |  | User Name in User Master Record |
| 6 | `SUP_COND_REQ` | CHAR | 1 |  | Supply Condition Letter required |
| 7 | `REINF_SCHEME_NO` | CHAR | 40 |  | Project Scheme No. |
| 8 | `REINF_APP_LOAD` | DEC | 9 |  | Approved Loading |
| 9 | `REINF_ACT_DEPOSIT` | CHAR | 15 |  | Actual Deposit Amount |
| 10 | `REINF_LEAD_TIME` | CHAR | 3 |  | Estimated reinforcement lead time |
| 11 | `REINF_COMM_DATE` | DATS | 8 |  | Estimated extended reinforcement commissioning date |
| 12 | `REINF_EXT_REASON` | CHAR | 100 |  | Reason of Extension |
| 13 | `SLIP_REC_DATE` | DATS | 8 |  | Condition Letter Reply Slip Received Date |
| 14 | `DEP_REF_DATE` | DATS | 8 |  | Deposit Refund date |
| 15 | `PHASE1_SO` | CHAR | 12 |  | Phase 1 Service Order |
| 16 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 17 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 18 | `ERZET` | TIMS | 6 |  | Entry time |
| 19 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 20 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 21 | `AEZET` | TIMS | 6 |  | Time last change was made |
