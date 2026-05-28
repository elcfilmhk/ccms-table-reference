# ZISCSIBRCONF
**Description:** IBR Block Percentages
**Total Fields:** 4
**Key Fields:** MANDT, DSMPROGID, IBRPRICEBLOCK

## Programs Using This Table
- `ziscrm0319`
- `ziscs0711`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `DSMPROGID` | CHAR | 6 | 🔑 | DSM Program ID |
| 3 | `IBRPRICEBLOCK` | INT4 | 10 | 🔑 | IBR Price Block |
| 4 | `PERC_LIMIT` | CHAR | 3 |  | % Limit for Block |
