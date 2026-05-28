# ZISDMGRPBILLEST
**Description:** Group Bill Estimation Table
**Total Fields:** 19
**Key Fields:** MANDT, GRP_ACCT, CHILD_ACCT, DEVICE, ZWNUMMER, ADATSOLL

## Programs Using This Table
- `zisdm0050`
- `zisdm0156`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GRP_ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CHILD_ACCT` | CHAR | 12 | 🔑 | Contract Account Number |
| 4 | `DEVICE` | CHAR | 18 | 🔑 | Device |
| 5 | `ZWNUMMER` | NUMC | 3 | 🔑 | Register |
| 6 | `ADATSOLL` | DATS | 8 | 🔑 | Scheduled meter reading date |
| 7 | `CUST_NAME` | CHAR | 80 |  | Customer name entered |
| 8 | `NUM_EST` | DEC | 2 |  | Number of consecutive estimation |
| 9 | `AUTO_COMP` | CHAR | 1 |  | Auto MRO Completion |
| 10 | `ACT_MRD` | DATS | 8 |  | Actual meter reading date |
| 11 | `PORTION` | CHAR | 8 |  | Portion |
| 12 | `ALT_PORTION` | CHAR | 8 |  | Alternative portion |
| 13 | `ABLEINH` | CHAR | 8 |  | Meter reading unit |
| 14 | `ZAHLKOND` | CHAR | 4 |  | Payment Condition |
| 15 | `TARIFTYP` | CHAR | 10 |  | Rate category |
| 16 | `MASTER_SUB_IND` | CHAR | 1 |  | Master-sub indicator |
| 17 | `ABLSTAT` | CHAR | 1 |  | Meter Reading Status |
| 18 | `CONSUMPTION` | NUMC | 12 |  | Consumption of the MRO |
| 19 | `ACTION` | CHAR | 1 |  | The action to be taken |
