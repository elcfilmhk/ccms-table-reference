# ZISCS_ENTL_ITEM
**Description:** Entitlement Line Items Tracking Table
**Total Fields:** 22
**Key Fields:** MANDT, VKONT, CPUDT, CPUTM, SEQ

## Programs Using This Table
- `z_cs_cxt_ca_list`
- `zccgvt10`
- `ziscs0218`
- `ziscs0219`
- `ziscs0220`
- `ziscs0222`
- `ziscs0224`
- `ziscs0225`
- `ziscs0226`
- `ziscs0226a`
- `ziscs0226b`
- `ziscs0226c`
- `ziscs0226d`
- `ziscs0226e`
- `ziscs0226f`
- `ziscs0226g`
- `ziscs0243`
- `ziscs0244`
- `ziscs0251`
- `ziscs0293`
- `ziscs0342`
- `ziscs0360`
- `ziscs0362`
- `ziscs0540`
- `ziscs0831`
- `ziscs0859`
- `ziscs0892`
- `ziscsgovsubmreverse`
- `zisfi0349`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CPUDT` | DATS | 8 | 🔑 | Date of entry |
| 4 | `CPUTM` | TIMS | 6 | 🔑 | Time of Entry |
| 5 | `SEQ` | NUMC | 2 | 🔑 | Sequence number for Gov subsidy |
| 6 | `PROCID` | CHAR | 12 |  | Process ID |
| 7 | `ANLAGE` | CHAR | 10 |  | Installation |
| 8 | `VERTRAG` | CHAR | 10 |  | Contract |
| 9 | `REFMTH` | DATS | 8 |  | Entitlement ref month |
| 10 | `ERNAM` | CHAR | 12 |  | Created By |
| 11 | `BELNR` | CHAR | 12 |  | Billing document number of the invoice |
| 12 | `PRINTDOC` | CHAR | 12 |  | Print document number |
| 13 | `REVDOC` | CHAR | 12 |  | Reversal print document number |
| 14 | `BUDAT` | DATS | 8 |  | Posting Date in the Document |
| 15 | `BALENT` | CURR | 13 |  | Entitlement balance |
| 16 | `ENTAMT` | CURR | 13 |  | Entitlement amount |
| 17 | `ENTVID` | CURR | 13 |  | Entitlement voided |
| 18 | `ENTUSG` | CURR | 13 |  | Entitlement usage |
| 19 | `EMTRES` | CURR | 13 |  | Usage rev |
| 20 | `FORFAMT` | CURR | 13 |  | Entitlement forfeiture amount |
| 21 | `FORFAMTREV` | CURR | 13 |  | Entitlement forfeiture amount reversal |
| 22 | `TRANSFER_FROM_CA` | CHAR | 12 |  | Transfer From Contract Account (Old) |
