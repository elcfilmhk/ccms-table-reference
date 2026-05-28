# ZISCEP_EHER_CLIK
**Description:** Logs for the customers clicking the hyperlinks
**Total Fields:** 6
**Key Fields:** MANDT, TRACKING_DATE, TRACKING_TIME, CONTRACT_ACCOUNT, EMAIL_GUID, URL_GUID

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
| 6 | `URL_GUID` | CHAR | 32 | 🔑 | CEP: e-HER URL GUID |
