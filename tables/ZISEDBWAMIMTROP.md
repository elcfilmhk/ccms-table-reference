# ZISEDBWAMIMTROP
**Description:** Export table for daily extraction of AMI profile value to BW
**Total Fields:** 8
**Key Fields:** MANDT, SNAP_DATE, SNAP_TIME, SERNR

## Programs Using This Table
- `zised0045`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SNAP_DATE` | DATS | 8 | 🔑 | Date (Snapshot) |
| 3 | `SNAP_TIME` | TIMS | 6 | 🔑 | Time (Snapshot) |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `ZCMRDATE` | DATS | 8 |  | Profile date, normally Snapshot date - 1 |
| 6 | `VKONTO` | CHAR | 12 |  | Contract Account Number |
| 7 | `ZCMPROFLG` | CHAR | 3 |  | With Profile Value (Y: All meter has profile value) |
| 8 | `ANLAGE` | CHAR | 10 |  | Installation |
