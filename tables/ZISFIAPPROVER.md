# ZISFIAPPROVER
**Description:** Approver Table for Credit Control Workflow
**Total Fields:** 11
**Key Fields:** MANDT, ZZKEY, ZZTYPES, OPBEL, OPUPK, ZZTIMESTAMP

## Programs Using This Table
- `z_get_approver================ft`
- `zca_doc`
- `zisfi0091`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZKEY` | CHAR | 7 | 🔑 | Transaction Key |
| 3 | `ZZTYPES` | CHAR | 1 | 🔑 | Transaction Type |
| 4 | `OPBEL` | CHAR | 12 | 🔑 | Document Number in Contract Accounts Receivable and Payable |
| 5 | `OPUPK` | NUMC | 4 | 🔑 | Item number in contract account document |
| 6 | `ZZTIMESTAMP` | CHAR | 20 | 🔑 | Time Stamp |
| 7 | `ZZAPPROVER` | CHAR | 14 |  | Approver |
| 8 | `ZZAMOUNT` | CURR | 13 |  | Amount |
| 9 | `WAERS` | CUKY | 5 |  | Currency Key |
| 10 | `HVORG` | CHAR | 4 |  | Main Transaction for Line Item |
| 11 | `ZZDEFER` | CHAR | 14 |  | Defer to Date/Payement method |
