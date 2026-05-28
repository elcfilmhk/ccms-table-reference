# ZISDMZEOCSMPIN
**Description:** Meter inspection MRO tracking
**Total Fields:** 15
**Key Fields:** MANDT, ZSR_WORK_ORDER, DEVICE_NO

## Programs Using This Table
- `zisdm0050`
- `zisdm0173`
- `zisdm0174`
- `zisdm0175`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZSR_WORK_ORDER` | CHAR | 12 | 🔑 | Order Number |
| 3 | `DEVICE_NO` | CHAR | 18 | 🔑 | Device |
| 4 | `CREATION_DATE` | DATS | 8 |  | Date on Which Record Was Created |
| 5 | `INSTALLATION` | CHAR | 10 |  | Installation |
| 6 | `ACCOUNT_NO` | CHAR | 12 |  | Contract Account Number |
| 7 | `PREMISE` | CHAR | 10 |  | Premise |
| 8 | `AMR_IND` | CHAR | 1 |  | Device is read by AMRS/RMR indicator |
| 9 | `MR_DATE` | DATS | 8 |  | Meter reading date relevant to billing |
| 10 | `INSTRCODE` | CHAR | 2 |  | Instruction Code |
| 11 | `MRJOB_STATUS` | CHAR | 1 |  | Job status of the Meter Reading |
| 12 | `READCODE` | NUMC | 2 |  | Cant' Read Code |
| 13 | `ZMI_AUFNR` | CHAR | 12 |  | Order Number |
| 14 | `ZMI_ERDAT` | DATS | 8 |  | Date on Which Record Was Created |
| 15 | `CAT_DESC` | CHAR | 30 |  | Category Description |
