# ZISDMESMTR
**Description:** Storing essential meter list
**Total Fields:** 9
**Key Fields:** MANDT, SERNR

## Programs Using This Table
- `zisdm0247`
- `zisdm0248`
- `zisdm0249`
- `zisdm0250`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 3 | `MTH1` | DEC | 2 |  | First Preferred Month of SMRD |
| 4 | `MTH2` | DEC | 2 |  | Second Preferred Month of SMRD |
| 5 | `MTH3` | DEC | 2 |  | Third Preferred Month of SMRD |
| 6 | `RR_MTH` | DEC | 2 |  | Reliable reading months |
| 7 | `WORKDAY` | DEC | 2 |  | No. of working days for aperiodic MRO creation |
| 8 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 9 | `ADATSOLL` | DATS | 8 |  | Scheduled meter reading date |
