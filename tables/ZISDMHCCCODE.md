# ZISDMHCCCODE
**Description:** Inst. code to determine what SMS message to send to customer
**Total Fields:** 6
**Key Fields:** MANDT, AUFNR

## Programs Using This Table
- `ziscs0462`
- `zisdm0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUFNR` | CHAR | 12 | 🔑 | Order Number |
| 3 | `ABLBELNR` | CHAR | 20 |  | Internal ID for meter reading document |
| 4 | `CHANGECODE1` | CHAR | 2 |  | Changed Note Indicator |
| 5 | `BATCH_DATE` | DATS | 8 |  | Field of type DATS |
| 6 | `ADAT` | DATS | 8 |  | Meter reading date relevant to billing |
