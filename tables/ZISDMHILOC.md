# ZISDMHILOC
**Description:** Hi-Lo Complaint Data for MR Upload
**Total Fields:** 6
**Key Fields:** MANDT, RUNDATE, GPART, VKONT

## Programs Using This Table
- `zisdm0050`
- `zisdm0097`
- `zisdm0162`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `RUNDATE` | DATS | 8 | 🔑 | Date |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `STATUS` | NUMC | 4 |  | Status Counter |
| 6 | `AUFNR` | CHAR | 12 |  | Order Number |
