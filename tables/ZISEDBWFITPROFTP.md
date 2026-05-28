# ZISEDBWFITPROFTP
**Description:** Temp Table for FiT Load Profile Extraction
**Total Fields:** 11
**Key Fields:** MANDT, PROFILE

## Programs Using This Table
- `zised0067`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROFILE` | NUMC | 18 | 🔑 | Number of EDM Profile |
| 3 | `SERNR` | CHAR | 18 |  | Serial Number |
| 4 | `METER_TYPE` | CHAR | 1 |  | Meter Type |
| 5 | `ZWNUMMER` | NUMC | 3 |  | Register |
| 6 | `KENNZIFF` | CHAR | 15 |  | Code for Identifying a Register |
| 7 | `VKONT` | CHAR | 12 |  | Contract Account Number |
| 8 | `MASSBILL` | UNIT | 3 |  | Unit of measurement for meter reading |
| 9 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 10 | `DATEFROM` | DATS | 8 |  | From-Date |
| 11 | `DATETO` | DATS | 8 |  | To-Date |
