# ZISCSPC_WCOFFER
**Description:** Welcome Offer Table
**Total Fields:** 14
**Key Fields:** MANDT, PROD_ID, MERCHANTID, PROG_ID

## Programs Using This Table
- `ziscs0727`
- `ziscs0808`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROD_ID` | CHAR | 3 | 🔑 | Product ID |
| 3 | `MERCHANTID` | CHAR | 3 | 🔑 | Merchant ID |
| 4 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 5 | `PROD_DESC` | CHAR | 40 |  | Product Description |
| 6 | `VALIDFROM` | DATS | 8 |  | Valid From Date |
| 7 | `VALIDTO` | DATS | 8 |  | Valid To Date |
| 8 | `REDEMPTION_EXPIRE_DATE` | DATS | 8 |  | Redemption expire date |
| 9 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 10 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 11 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 12 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 13 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 14 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
