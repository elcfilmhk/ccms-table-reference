# ZISDMMTRMD
**Description:** TOU Meter Model, Comm Method, Act Type and Register Codes
**Total Fields:** 18
**Key Fields:** MANDT, OBJECTTYPE, METERMODEL

## Programs Using This Table
- `zisdh0002`
- `zisdh0004`
- `zisdh0021`
- `zisdm0027`
- `zisdm0049`
- `zisdm0050`
- `zisdm0051`
- `zisdm0052`
- `zisdm0082`
- `zisdm0407`
- `zisdm0409`
- `zisdm0413`
- `zrdm_dr_rep`
- `zrdm_m_repl_rep`
- `zrdm_us_rep`
- `zrdm_wd_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `OBJECTTYPE` | CHAR | 10 | 🔑 | Type of Technical Object |
| 3 | `METERMODEL` | CHAR | 20 | 🔑 | Manufacturer model number |
| 4 | `TYPEOFMETER` | CHAR | 1 |  | Type of Meter set to 'T' or 'M' |
| 5 | `TOUMODEL` | CHAR | 2 |  | TOU ITRON Meter Model - Default 'O' |
| 6 | `COMMMETHOD` | CHAR | 1 |  | Communication Method |
| 7 | `ACTTYPE01` | CHAR | 1 |  | Mechanical Read Indicator |
| 8 | `ACTTYPE12` | CHAR | 1 |  | Reset Time Indicator |
| 9 | `ACTTYPE13` | CHAR | 1 |  | TOU Reset Demand Indicator |
| 10 | `ACTTYPE21` | CHAR | 1 |  | TOU Read Registers Indicator |
| 11 | `ACTTYPE22` | CHAR | 1 |  | TOU Read Load Profile Indicator |
| 12 | `ACTTYPE24` | CHAR | 1 |  | TO Read Partial Load Profile |
| 13 | `REGCODEPD` | CHAR | 1 |  | Reprogramming Date |
| 14 | `REGCODELS` | CHAR | 1 |  | Reset Count |
| 15 | `REGCODEPC` | CHAR | 1 |  | Reprogram Count |
| 16 | `REGCODEAD` | CHAR | 1 |  | Reprogramming Rate ID. |
| 17 | `NOSTDPPM` | CHAR | 1 |  | Non-standard PPM Indicator |
| 18 | `RESREGCD` | CHAR | 2 |  | Reset Register code for Non-Standard PPM |
