# ZISBI_GS_ITEM
**Description:** Government Subsidy Line Items Tracking Table
**Total Fields:** 32
**Key Fields:** MANDT, SCHEME, VKONT, ERDAT, ERZEIT, SEQ

## Programs Using This Table
- `zisfi0314`
- `zisfi0316`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCHEME` | CHAR | 6 | 🔑 | Scheme |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 5 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 6 | `SEQ` | NUMC | 3 | 🔑 | Seq No. |
| 7 | `PROCID` | CHAR | 12 |  | Process ID |
| 8 | `STATUS` | CHAR | 1 |  | Status |
| 9 | `BD` | CHAR | 12 |  | Number of a billing document |
| 10 | `PD` | CHAR | 12 |  | Number of print document |
| 11 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 12 | `REV_PD` | CHAR | 12 |  | Reversal PD No. |
| 13 | `REV_BUDAT` | DATS | 8 |  | Reversal PD Posting Date |
| 14 | `BILL_FR` | DATS | 8 |  | Bill Start |
| 15 | `BILL_TO` | DATS | 8 |  | Bill End |
| 16 | `BILL_DAY` | INT4 | 10 |  | No. of Bill Days |
| 17 | `BILL_AMT` | CURR | 13 |  | Bill Amount |
| 18 | `GS_FR` | DATS | 8 |  | Gov Subsidy Start |
| 19 | `GS_TO` | DATS | 8 |  | Gov Subsidy End |
| 20 | `GS_DAY` | INT4 | 10 |  | No. of Gov Subsidy Day |
| 21 | `BILL_AMT_GS` | CURR | 18 |  | Bill Amount for Subsidy Calculation |
| 22 | `PERCENT` | DEC | 6 |  | Gov Subsidy Percentage |
| 23 | `GS_ORG` | CURR | 13 |  | Gov Subsidy (Original) |
| 24 | `CAP_AMT` | CURR | 13 |  | Gov Subsidy Cap Amount |
| 25 | `GS` | CURR | 13 |  | Gov Subsidy |
| 26 | `GS_NET` | CURR | 13 |  | Net Gov Subsidy |
| 27 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 28 | `ACTPERIOD` | CHAR | 4 |  | Category of a period for current billing |
| 29 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 30 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 31 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
| 32 | `REMARK` | CHAR | 40 |  | Remark |
