# ZISCSSER_HDR
**Description:** eService Header
**Total Fields:** 10
**Key Fields:** MANDT, VKONT, TYPE, DISPATCH

## Programs Using This Table
- `zisbi0084`
- `ziscs0134`
- `ziscs0158`
- `ziscs0160`
- `ziscs0169`
- `ziscs0278`
- `ziscs0280`
- `ziscs0331`
- `ziscs0333`
- `ziscs0334`
- `ziscs0338`
- `ziscs0346`
- `ziscs0347`
- `ziscs0348`
- `ziscs0349`
- `ziscs0352`
- `ziscs0371`
- `ziscs0377`
- `ziscs0379`
- `ziscs0484`
- `ziscs_migration_account_notif`
- `ziscsconvert_bill_pay`
- `ziscsconvert_bp_alerts`
- `ziscsconvert_con_alert`
- `zisdm0278`
- `zisfi0239`
- `zrca_ssr_cust_extract`
- `zrca_ssr_program_upload`
- `zrcs_cons_af_rep`
- `zrcs_remove_cons_af`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `TYPE` | CHAR | 1 | 🔑 | Type of eService |
| 4 | `DISPATCH` | CHAR | 1 | 🔑 | Dispatch |
| 5 | `GPART` | CHAR | 10 |  | Business Partner Number |
| 6 | `STATUS` | CHAR | 1 |  | Status |
| 7 | `ERDAT` | CHAR | 14 |  | Creation Date |
| 8 | `ERNAM` | CHAR | 12 |  | Create By |
| 9 | `AEDAT` | CHAR | 14 |  | Change Date |
| 10 | `AENAM` | CHAR | 12 |  | Change By |
