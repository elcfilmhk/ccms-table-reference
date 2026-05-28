# ZISCRMCCARDDIFF
**Description:** Credit card with from date discrepancy
**Total Fields:** 10
**Key Fields:** CLIENT, CCARD_GUID

## Programs Using This Table
- `ziscrm_comp_pcamaster_fromdate`
- `ziscrm_update_pca_fromdate`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `CCARD_GUID` | RAW | 16 | 🔑 | GUID of a Payment Card |
| 3 | `CRDATE` | DATS | 8 |  | Creation date in change history |
| 4 | `DUPLICATE` | CHAR | 1 |  | Duplicate credit card entry indicator |
| 5 | `PROCESSED` | CHAR | 1 |  | Processed record indicator |
| 6 | `PROCDATE` | DATS | 8 |  | Process date |
| 7 | `PROCTIME` | TIMS | 6 |  | Process time |
| 8 | `PROCUSER` | CHAR | 12 |  | Process user |
| 9 | `NO_CRM_PCA` | CHAR | 1 |  | CRM PCA_MASTER record not found |
| 10 | `CLEARISSUDATE` | CHAR | 1 |  | Clear Issuing Date indicator |
