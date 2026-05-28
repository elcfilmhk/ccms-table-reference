# ZISCEPINFO
**Description:** Customer Engagement Platform (CEP) Info for Contract Account
**Total Fields:** 19
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `ziscs0099`
- `ziscs0386_eec`
- `ziscs0387_eec`
- `ziscs0391_eec`
- `ziscs0454`
- `ziscs0456`
- `ziscs0458`
- `ziscs0459`
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `FOOTAGE` | INT4 | 10 |  | CEP: Footage |
| 4 | `SEGMENT` | CHAR | 3 |  | Customer Segment |
| 5 | `HER_LANG` | CHAR | 1 |  | CEP: Home Energy Report (HER) Language |
| 6 | `STATUS` | CHAR | 1 |  | Customer Status |
| 7 | `OPT_IN_DATE` | DATS | 8 |  | CEP: HER Opt-In Date |
| 8 | `OPT_OUT_DATE` | DATS | 8 |  | CEP: HER Opt-Out Date |
| 9 | `OPT_OUT_REASON` | CHAR | 4 |  | CEP: HER Opt-Out Reason |
| 10 | `CONSUMPTION` | DEC | 13 |  | Consumption |
| 11 | `TTL_ENQUIRIES` | INT4 | 10 |  | Total Enquiries |
| 12 | `LAST_METER_READ` | DATS | 8 |  | Last meter reading date |
| 13 | `LOGIN_FAIL_COUNT` | INT4 | 10 |  | CEP: Login Fail Count |
| 14 | `EHER_OPT_IN_DATE` | DATS | 8 |  | CEP: e-HER Opt-In Date |
| 15 | `EHER_OPT_OUT_DAT` | DATS | 8 |  | CEP: e-HER Opt-Out Date |
| 16 | `EHER_OPT_OUT_REA` | CHAR | 4 |  | CEP: e-HER Opt-Out Reason |
| 17 | `FIRST_LOGIN_DATE` | DATS | 8 |  | CEP: First Login Date |
| 18 | `LT_LOGIN_DATE` | DATS | 8 |  | CEP: Last Login Date |
| 19 | `LT_LOGIN_TIME` | TIMS | 6 |  | CEP: Last Login Time |
