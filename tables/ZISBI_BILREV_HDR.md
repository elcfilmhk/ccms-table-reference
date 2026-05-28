# ZISBI_BILREV_HDR
**Description:** Bill Reversal Header
**Total Fields:** 23
**Key Fields:** MANDT, VKONT, ITEMNUMBER, ERDAT, ERZET

## Programs Using This Table
- `z_isbi_process_bill_method_chgft`
- `zisbi0234`
- `zisbi_dsm_logreport`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `ITEMNUMBER` | CHAR | 3 | 🔑 | Item Number |
| 4 | `ERDAT` | DATS | 8 | 🔑 | Date |
| 5 | `ERZET` | TIMS | 6 | 🔑 | Entry time |
| 6 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
| 7 | `VERTRAG` | CHAR | 10 |  | Contract |
| 8 | `EFFECTIVE_DATE` | DATS | 8 |  | Effective Date |
| 9 | `STATUS` | CHAR | 1 |  | Overall Status |
| 10 | `ACTIVITY` | CHAR | 5 |  | Activity |
| 11 | `CLEARING_RESET` | CHAR | 1 |  | Reset Clearing |
| 12 | `INVOICE_REVERSAL_FLAG` | CHAR | 1 |  | Invoice Reversal Flag |
| 13 | `BILL_REVERESAL_FLAG` | CHAR | 1 |  | Bill Reversal Flag |
| 14 | `REG_UPD_FLAG` | CHAR | 1 |  | Register Update Flag |
| 15 | `INST_FACT_UPD_FLAG` | CHAR | 1 |  | Installation FACTS Update Flag |
| 16 | `REBILL_FLAG` | CHAR | 1 |  | Rebill Flag |
| 17 | `REINVOICE_FLAG` | CHAR | 1 |  | Re-Invoicing Flag |
| 18 | `REG_UPD_ERROR` | CHAR | 220 |  | Message Text |
| 19 | `INST_FACT_UPD_ERROR` | CHAR | 220 |  | Message Text |
| 20 | `OUTBOUND_COMM` | CHAR | 1 |  | Outbound Communication Flag |
| 21 | `CURR_DSM_GROUP` | CHAR | 8 |  | Current DSM Group for CA |
| 22 | `NEW_DSM_GROUP` | CHAR | 8 |  | New DSM Group for CA |
| 23 | `LASTBILLPERERROR` | CHAR | 220 |  | Message Text |
