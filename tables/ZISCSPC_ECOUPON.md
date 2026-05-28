# ZISCSPC_ECOUPON
**Description:** Custom Table for Mass upload of eCoupon
**Total Fields:** 13
**Key Fields:** MANDT, PROG_ID, QRCODEMAP

## Programs Using This Table
- `ziscs0808`
- `ziscs0810`
- `ziscs0810a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `QRCODEMAP` | CHAR | 30 | 🔑 | QR Code MApping |
| 4 | `MERCHANTID` | CHAR | 3 |  | Merchant ID |
| 5 | `ECOUPONID` | CHAR | 3 |  | Product ID |
| 6 | `CODETYPE` | CHAR | 10 |  | Code Type |
| 7 | `QRCODEENC` | CHAR | 100 |  | QR  Code  Encryption |
| 8 | `USED_STATUS` | CHAR | 1 |  | Used Status Indicator |
| 9 | `CRUSR` | CHAR | 12 |  | User Who Created the Object |
| 10 | `CRDAT` | DATS | 8 |  | Date on which the object was created |
| 11 | `CRTIM` | TIMS | 6 |  | Time at which the object was created |
| 12 | `CHUSR` | CHAR | 12 |  | Last user to change object |
| 13 | `CHDAT` | DATS | 8 |  | Date when object was last changed |
