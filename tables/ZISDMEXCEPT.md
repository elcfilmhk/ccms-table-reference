# ZISDMEXCEPT
**Description:** Exception for EV_TOU Delay process
**Total Fields:** 5
**Key Fields:** MANDT, ANLAGE, SERNR, SCH_END_DATE

## Programs Using This Table
- `zrvee_pre_bill_estimation`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ANLAGE` | CHAR | 10 | 🔑 | Installation |
| 3 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 4 | `SCH_END_DATE` | DATS | 8 | 🔑 | Scheduled Billing End Date |
| 5 | `STATUS` | CHAR | 1 |  | Process Status |
