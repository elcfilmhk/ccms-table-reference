# ZISBIEBILL
**Description:** eBill Statistics Report
**Total Fields:** 11
**Key Fields:** MANDT, GPART, VKONT, DISPATCH, OPBEL, WEDAT

## Programs Using This Table
- `zisbi0003`
- `zisbi0022`
- `zisbi0067`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 3 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `DISPATCH` | CHAR | 4 | 🔑 | Dispatch Control |
| 5 | `OPBEL` | CHAR | 12 | 🔑 | Number of print document |
| 6 | `WEDAT` | DATS | 8 | 🔑 | Delivery date |
| 7 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 8 | `BOUNCE` | CHAR | 1 |  | Bounced Indicator |
| 9 | `FAILED` | CHAR | 1 |  | Failed Indicator |
| 10 | `BOUNCEDATE` | DATS | 8 |  | Email Bounce date |
| 11 | `BATCHDATE` | DATS | 8 |  | Batch run date |
