# ZISCS_SUB_RFDATE
**Description:** Government Subsidy Entitlement Validity Master Data
**Total Fields:** 16
**Key Fields:** MANDT, DDTEXT, BEGDT

## Programs Using This Table
- `ziscs0219`
- `ziscs0219_a`
- `ziscs0220`
- `ziscs0222`
- `ziscs0223`
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
- `ziscs0342`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DDTEXT` | CHAR | 30 | 🔑 | Subsidy key |
| 3 | `BEGDT` | DATS | 8 | 🔑 | From date |
| 4 | `ENDDT` | DATS | 8 |  | To date |
| 5 | `MAXAMT` | CURR | 13 |  | Maximum subisdy allowed |
| 6 | `VALIDTO` | DATS | 8 |  | Subsidy end date |
| 7 | `INV` | CHAR | 1 |  | Invoicing (R402) |
| 8 | `INVREV` | CHAR | 1 |  | Invoicing Reversal (R471) |
| 9 | `MADJENTL` | CHAR | 1 |  | Manual Adjust Entitlement (SAPMZCS13) |
| 10 | `IDFYACENTL` | CHAR | 1 |  | Identify AC for Entitlement (ZISCS0222) |
| 11 | `MIMO` | CHAR | 1 |  | Move In/Out (ZXES20F01) |
| 12 | `ENTLRPT` | CHAR | 1 |  | Entitlement Report (ZISCS0226A) |
| 13 | `VGSSENTLGRNT` | CHAR | 1 |  | Verify GSS Entitlement Grant(ZISCS0219) |
| 14 | `SSBALSNPST` | CHAR | 1 |  | Subsidy Balance Snapshot(ZISCS0218) |
| 15 | `SCHEME` | CHAR | 10 |  | Scheme of Gov Subsidy |
| 16 | `ACT_ENTL_DT` | DATS | 8 |  | Actual Entitlement Date |
