# ZISDMLPBCVLIST
**Description:** Installations to be converted to load profile for Billing
**Total Fields:** 13
**Key Fields:** MANDT, ANLAGE, ADATSOLL

## Programs Using This Table
- `zisdm0200`
- `zisdm0201`
- `zisdm0201_main`
- `zisdm0201_sub_gp`
- `zisdm0201_sub_lp`
- `zisdm0202`
- `zisdm0203`
- `zisdm0203_cbtolp`
- `zisdm0203_rbtolp`
- `zisdm0204`
- `zisdm0205`
- `zisdm0213`
- `zisdm0294`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 4 | `RTP_OFFSET` | TIMS | 6 |  | Day Offset |
| 5 | `MANUAL_CONVERT` | CHAR | 1 |  | Manual Conversion Indicator |
| 6 | `SUBTRACT_KVA` | CHAR | 1 |  | KVA subtraction by load profile |
| 7 | `STATUS` | CHAR | 1 |  | Status of the conversion |
| 8 | `GB_OUTSORT` | CHAR | 1 |  | Indicator for outsort group bill |
| 9 | `GB_ADATSOLL` | DATS | 8 |  | Group bill scheduled reading date |
| 10 | `ACTION` | CHAR | 1 |  | Action (Cancelled or Reading complete) |
| 11 | `LAST_CHG_USERID` | CHAR | 12 |  | Name of person who changed object |
| 12 | `LAST_CHG_DATE` | DATS | 8 |  | Date of Last Change |
| 13 | `SCENARIO` | CHAR | 20 |  | Scenario Description |
