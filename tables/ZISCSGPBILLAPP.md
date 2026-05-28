# ZISCSGPBILLAPP
**Description:** Group bill application queue
**Total Fields:** 13
**Key Fields:** MANDT, CHILD_CA

## Programs Using This Table
- `ziscs0246`
- `ziscs0247`
- `ziscs0248`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CHILD_CA` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CA_NAME` | CHAR | 35 |  | Contract Account Name |
| 4 | `PARENT_CA` | CHAR | 12 |  | Contract Account Number |
| 5 | `DISPATCH_CONT` | CHAR | 4 |  | Dispatch control for original customer |
| 6 | `ADDITIONAL_BILL` | CHAR | 1 |  | Send additional bill to business partner |
| 7 | `PAYMENT_COND` | CHAR | 4 |  | Payment Condition |
| 8 | `ALT_PORTION` | CHAR | 8 |  | Alternative portion |
| 9 | `STATUS` | CHAR | 20 |  | Status |
| 10 | `CREATED_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 11 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
| 13 | `CHANGED_BY` | CHAR | 12 |  | Name of person who changed object |
