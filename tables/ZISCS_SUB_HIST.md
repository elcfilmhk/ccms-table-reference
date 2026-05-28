# ZISCS_SUB_HIST
**Description:** Government Subsidy Migration History table
**Total Fields:** 13
**Key Fields:** MANDT, VERSION, ENTRY_DATE, VKONT, SEQ_NO, SCHEME

## Programs Using This Table
- `ziscs0860_new`
- `ziscs0861`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VERSION` | NUMC | 2 | 🔑 | Sequence number |
| 3 | `ENTRY_DATE` | DATS | 8 | 🔑 | Creation date |
| 4 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 5 | `SEQ_NO` | NUMC | 2 | 🔑 | Sequence number for Gov subsidy |
| 6 | `SCHEME` | CHAR | 10 | 🔑 | Scheme of Gov Subsidy |
| 7 | `ENTAMT` | CURR | 13 |  | Entitlement amount |
| 8 | `ENTUSG` | CURR | 13 |  | Entitlement usage |
| 9 | `FORFAMT` | CURR | 13 |  | Entitlement forfeiture amount |
| 10 | `BALSUBS` | CURR | 13 |  | Entitlement subsidy balance |
| 11 | `SUPP_SUBSIDY` | CURR | 13 |  | Entitlement amount |
| 12 | `CREATE_DATE` | DATS | 8 |  | Creation date |
| 13 | `CREATE_TIME` | TIMS | 6 |  | Creation Time |
