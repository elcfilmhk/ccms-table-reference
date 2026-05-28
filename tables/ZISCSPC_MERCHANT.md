# ZISCSPC_MERCHANT
**Description:** Merchant Master Table for PC
**Total Fields:** 14
**Key Fields:** MANDT, PROG_ID, MERCHANTID, ECOUPONID

## Programs Using This Table
- `ziscs0808`
- `ziscs0810`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `MERCHANTID` | CHAR | 3 | 🔑 | Merchant ID |
| 4 | `ECOUPONID` | CHAR | 3 | 🔑 | Product ID |
| 5 | `MERCHANTNAME` | CHAR | 80 |  | Merchant Name |
| 6 | `VALIDFROM` | DATS | 8 |  | Valid From Date |
| 7 | `VALIDTO` | DATS | 8 |  | Valid To Date |
| 8 | `STATUS` | CHAR | 1 |  | Status for Merchant in PC |
| 9 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 10 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 11 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 12 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 13 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
| 14 | `CHTIM` | TIMS | 6 |  | Time at which object was last changed |
