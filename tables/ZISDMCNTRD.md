# ZISDMCNTRD
**Description:** Can't Read Code Table
**Total Fields:** 14
**Key Fields:** MANDT, READCODE

## Programs Using This Table
- `zisbi0029`
- `zisdh0002`
- `zisdh0004`
- `zisdm0027`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0051`
- `zisdm0082`
- `zisdm0260`
- `zisdm0407`
- `zisdm0409`
- `zisdm0411`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `READCODE` | NUMC | 2 | 🔑 | Cant' Read Code |
| 3 | `ABREVIATION` | CHAR | 14 |  | Abbreviation Code |
| 4 | `DESCRIPTION` | CHAR | 40 |  | Code Description |
| 5 | `BTLLPTBILLREQD` | CHAR | 1 |  | Indicator to show whether billing will be performed or not |
| 6 | `BTLPTCHECKREAD` | CHAR | 1 |  | Check read required indicator |
| 7 | `BTLPTSOTYPE` | CHAR | 4 |  | Service Order Type |
| 8 | `BTLPTACTTYPE` | CHAR | 6 |  | Activity Type |
| 9 | `BTLPTNOMETERREAD` | CHAR | 1 |  | Action required if no meter reading is recieved |
| 10 | `DTGSTBILLREQD` | CHAR | 1 |  | Indicator to show whether billing will be performed or not |
| 11 | `DTGSTCHECKREAD` | CHAR | 1 |  | Check read required indicator |
| 12 | `DTGSTSOTYPE` | CHAR | 4 |  | Service Order Type |
| 13 | `DTGSTACTTYPE` | CHAR | 6 |  | Activity Type |
| 14 | `DTGSTNOMETERREAD` | CHAR | 1 |  | Action required if no meter reading is recieved |
