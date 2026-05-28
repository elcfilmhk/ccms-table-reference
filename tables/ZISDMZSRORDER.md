# ZISDMZSRORDER
**Description:** Store supply add. and meter seal broken aperiodic MR upload
**Total Fields:** 11
**Key Fields:** MANDT, ZSR_WORK_ORDER

## Programs Using This Table
- `zisdm0050`
- `zisdm0233`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZSR_WORK_ORDER` | CHAR | 12 | 🔑 | Order Number |
| 3 | `DEVICE_NO` | CHAR | 18 |  | Device |
| 4 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 5 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
| 7 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 8 | `ILART` | CHAR | 3 |  | Maintenance activity type |
| 9 | `CANT_READ_CODE` | CHAR | 2 |  | Cannot Read Code |
| 10 | `INSTRUCTION_CODE` | CHAR | 2 |  | Instruction Code |
| 11 | `LAST_CHANGED_DAT` | DATS | 8 |  | Date of Last Change |
