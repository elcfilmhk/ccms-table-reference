# ZISMDDDSDATA
**Description:** Meter data processed in data driven schedule
**Total Fields:** 11
**Key Fields:** MANDT, BATCHDATE, MRU, INST, METER, SRD, CYC, PORTION, MOVEIN, POD, METER_TYPE

## Programs Using This Table
- `zismd0035`
- `zismd0035_nov17`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BATCHDATE` | DATS | 8 | 🔑 | Date |
| 3 | `MRU` | CHAR | 8 | 🔑 | Meter Reading Unit |
| 4 | `INST` | CHAR | 10 | 🔑 | Installation |
| 5 | `METER` | CHAR | 18 | 🔑 | Serial Number |
| 6 | `SRD` | DATS | 8 | 🔑 | Sch. MR date |
| 7 | `CYC` | CHAR | 2 | 🔑 | Cycle no. |
| 8 | `PORTION` | CHAR | 8 | 🔑 | Portion |
| 9 | `MOVEIN` | DATS | 8 | 🔑 | Move-In Date |
| 10 | `POD` | CHAR | 50 | 🔑 | Point of delivery ID |
| 11 | `METER_TYPE` | CHAR | 20 | 🔑 | Meter Type for Data Driven Schedule |
