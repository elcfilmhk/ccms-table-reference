# ZISDMEVTOL
**Description:** EV Vendor Tolerance Interval
**Total Fields:** 3
**Key Fields:** MANDT, VENDOR_ID

## Programs Using This Table
- `zisdm0223`
- `zisdm0226`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VENDOR_ID` | CHAR | 4 | 🔑 | The Vendor ID of the EV Vendor |
| 3 | `INTERVAL_TOL` | DEC | 13 |  | The consumption of the interval |
