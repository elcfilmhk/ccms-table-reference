# ZISBI_REB_DTL
**Description:** Rebate Detail
**Total Fields:** 22
**Key Fields:** MANDT, RB_YEAR, VKONT, VERTRAG, SEQ_NO, BELNR

## Programs Using This Table
- `zisbi0201`
- `zisbi0202`
- `zisbi0203`
- `zisbi0208`
- `zisbi0209`
- `zisbi0216`
- `zisbi0220`
- `zisbi0221`
- `zisfi0258`
- `zprintdoc`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RB_YEAR` | CHAR | 8 | 🔑 | Rebate year and reference |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `VERTRAG` | CHAR | 10 | 🔑 | Contract |
| 5 | `SEQ_NO` | NUMC | 3 | 🔑 | Seq No. |
| 6 | `BELNR` | CHAR | 12 | 🔑 | Number of a billing document |
| 7 | `AB` | DATS | 8 |  | Date from which time slice is valid |
| 8 | `BIS` | DATS | 8 |  | Date at Which a Time Slice Expires |
| 9 | `ANLAGE` | CHAR | 10 |  | Installation |
| 10 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 11 | `CONSUM` | DEC | 13 |  | Consumption consumed |
| 12 | `BILL_CONSUM` | DEC | 13 |  | Billed Consumption (KWH) |
| 13 | `ELIG_CONSUM` | DEC | 13 |  | Billed Consumption eligible for rebate |
| 14 | `REBATE` | CURR | 13 |  | Rebate Amount |
| 15 | `UNIT_RATE` | DEC | 17 |  | Rebate unit price |
| 16 | `NO_BILL_DAYS` | DEC | 10 |  | Number of billing days |
| 17 | `NO_REB_DAYS` | DEC | 10 |  | Number of days in rebate period |
| 18 | `STATTART` | CHAR | 8 |  | Rate type for statistical analysis |
| 19 | `ACTPERIOD` | CHAR | 4 |  | Category of a period for current billing |
| 20 | `ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 21 | `ERZEIT` | TIMS | 6 |  | Time, at Which Record Was Added |
| 22 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
