# ZISDMADRBATCHLOG
**Description:** ADR BATCH LOG table
**Total Fields:** 14
**Key Fields:** MANDT, LOGID

## Programs Using This Table
- `zisdm0309`
- `zisdm0310_adr`
- `zisdm0311_adr`
- `zisfi0249_dnld`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LOGID` | NUMC | 10 | 🔑 | DR Log ID |
| 3 | `BATCHID` | CHAR | 80 |  | Batch ID |
| 4 | `EVENTNAME` | CHAR | 50 |  | Event Name |
| 5 | `DRCUSTNO` | CHAR | 80 |  | DR Customer Number |
| 6 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 7 | `SERNR` | CHAR | 18 |  | Serial Number |
| 8 | `TYPE` | CHAR | 1 |  | Message Type |
| 9 | `MESSAGE` | CHAR | 73 |  | Message Text |
| 10 | `TCODE` | CHAR | 20 |  | Transaction Code |
| 11 | `REPID` | CHAR | 40 |  | ABAP Program Name |
| 12 | `LASTUPDATEDATE` | DATS | 8 |  | Date |
| 13 | `LASTUPDATETIME` | TIMS | 6 |  | Time |
| 14 | `LASTUPDATEBY` | CHAR | 12 |  | User Name |
