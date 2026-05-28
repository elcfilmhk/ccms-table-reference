# ZISCEP_EHER_OPEN
**Description:** Tracking log records when the customer opens the e-HER
**Total Fields:** 5
**Key Fields:** MANDT, TRACKING_DATE, TRACKING_TIME, CONTRACT_ACCOUNT, EMAIL_GUID

## Programs Using This Table
- `ziscs0463`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TRACKING_DATE` | DATS | 8 | 🔑 | CEP: e-HER Tracking Date |
| 3 | `TRACKING_TIME` | TIMS | 6 | 🔑 | CEP: e-HER Tracking Time |
| 4 | `CONTRACT_ACCOUNT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `EMAIL_GUID` | CHAR | 32 | 🔑 | CEP: e-HER Email GUID |
