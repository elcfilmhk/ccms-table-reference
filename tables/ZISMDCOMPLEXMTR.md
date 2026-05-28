# ZISMDCOMPLEXMTR
**Description:** Storing the MRO details for Complex billing account
**Total Fields:** 8
**Key Fields:** MANDT, MRU, INST, METER, SRD, CYC, PORTION, MOVEIN

## Programs Using This Table
- `zisdm0185`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MRU` | CHAR | 8 | 🔑 | Meter Reading Unit |
| 3 | `INST` | CHAR | 10 | 🔑 | Installation |
| 4 | `METER` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `SRD` | DATS | 8 | 🔑 | Sch. MR date |
| 6 | `CYC` | CHAR | 2 | 🔑 | Cycle no. |
| 7 | `PORTION` | CHAR | 8 | 🔑 | Portion |
| 8 | `MOVEIN` | DATS | 8 | 🔑 | Move-In Date |
