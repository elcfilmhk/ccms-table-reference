# ZISDMEVLPREJ
**Description:** Reject Session Table of Load Profile File Processing
**Total Fields:** 7
**Key Fields:** MANDT, VENDOR_ID, CHARGESTATION_ID, INT_START_DATE, SEQUENCE_NO

## Programs Using This Table
- `zisdm0220`
- `zisdm0225`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VENDOR_ID` | CHAR | 4 | 🔑 | The Vendor ID of the EV Vendor |
| 3 | `CHARGESTATION_ID` | CHAR | 32 | 🔑 | The ID of the charging station |
| 4 | `INT_START_DATE` | DATS | 8 | 🔑 | The start date of the interval |
| 5 | `SEQUENCE_NO` | NUMC | 8 | 🔑 | The Sequence Number for the run date |
| 6 | `ERROR_CODE` | CHAR | 3 |  | The Error Code of the exception |
| 7 | `CREATION_DATE` | DATS | 8 |  | The Creation Date of the reject Session |
