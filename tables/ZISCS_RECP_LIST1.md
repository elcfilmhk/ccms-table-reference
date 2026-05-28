# ZISCS_RECP_LIST1
**Description:** Recipient List Table (QR Code Alert)
**Total Fields:** 6
**Key Fields:** MANDT, PROG_ID, MERCHANTID, ROW_ID

## Programs Using This Table
- `ziscs0810`
- `ziscs0810a`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROG_ID` | CHAR | 8 | 🔑 | Programme ID |
| 3 | `MERCHANTID` | CHAR | 3 | 🔑 | Merchant ID |
| 4 | `ROW_ID` | CHAR | 5 | 🔑 | Row Id |
| 5 | `EMAILID` | CHAR | 30 |  | Customer Email ID |
| 6 | `ACTIVE` | CHAR | 1 |  | Active |
