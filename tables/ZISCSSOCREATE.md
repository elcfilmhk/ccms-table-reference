# ZISCSSOCREATE
**Description:** SO Creation Log based on Follow Up Order
**Total Fields:** 7
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0110`
- `ziscs0112`
- `ziscs0114`
- `ziscs0115`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `CREATEDATE` | DATS | 8 |  | SO Date of Creation |
| 4 | `TCOM_SENT` | CHAR | 1 |  | Sent To TCOM Indicator |
| 5 | `FOLLOWUP_ID` | CHAR | 24 |  | Follow Up Order ID |
| 6 | `INTERFACE_ID` | NUMC | 8 |  | Interface Run ID |
| 7 | `UPDERROR` | CHAR | 1 |  | System Error Indicator |
