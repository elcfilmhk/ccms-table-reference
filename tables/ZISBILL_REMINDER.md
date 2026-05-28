# ZISBILL_REMINDER
**Description:** Mobile push alert - billing reminder
**Total Fields:** 16
**Key Fields:** MANDT, ZDATE, ZTIME, ZSEQ

## Programs Using This Table
- `ziscs0718`
- `ziscs0720`
- `ziscs0732`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZDATE` | DATS | 8 | 🔑 | Date |
| 3 | `ZTIME` | TIMS | 6 | 🔑 | Time |
| 4 | `ZSEQ` | NUMC | 8 | 🔑 | Sequence |
| 5 | `PROJ` | CHAR | 20 |  | Project |
| 6 | `VKONT` | CHAR | 12 |  | CA |
| 7 | `TOKEN` | CHAR | 256 |  | Token |
| 8 | `LANG` | CHAR | 4 |  | language |
| 9 | `E_MSG` | CHAR | 500 |  | Message in Eng |
| 10 | `C_MSG` | CHAR | 500 |  | Message in Chinese |
| 11 | `SEGMENT` | CHAR | 200 |  | Segment |
| 12 | `S_TIME` | CHAR | 14 |  | Creation time |
| 13 | `D_TYPE` | CHAR | 12 |  | Device type |
| 14 | `MSG_TYPE` | CHAR | 12 |  | Message type |
| 15 | `CUST_DATA` | CHAR | 200 |  | Cust. Data |
| 16 | `ANALYTIC_TAG` | CHAR | 50 |  | Analytic tag |
