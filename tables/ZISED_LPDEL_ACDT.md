# ZISED_LPDEL_ACDT
**Description:** Load Profile Service Delivery Missing intervals- account lvl
**Total Fields:** 11
**Key Fields:** MANDT, REPORTDATE, SLADATE, VKONTO, SERVICETYPE, TARIFTYPSHORT, UNITOFMEASURE, STARTDATE, STARTTIME

## Programs Using This Table
- `zised0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPORTDATE` | DATS | 8 | 🔑 | Date |
| 3 | `SLADATE` | DATS | 8 | 🔑 | SLA Date |
| 4 | `VKONTO` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `SERVICETYPE` | CHAR | 2 | 🔑 | Load Profile Service Type |
| 6 | `TARIFTYPSHORT` | CHAR | 10 | 🔑 | Rate Category (Short) |
| 7 | `UNITOFMEASURE` | UNIT | 3 | 🔑 | Unit of measurement for meter reading |
| 8 | `STARTDATE` | DATS | 8 | 🔑 | Date |
| 9 | `STARTTIME` | TIMS | 6 | 🔑 | Time |
| 10 | `ENDDATE` | DATS | 8 |  | Date |
| 11 | `ENDTIME` | TIMS | 6 |  | Time |
