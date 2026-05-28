# ZISDMNUMDEV
**Description:** Custom table for Number of Devices
**Total Fields:** 4
**Key Fields:** MANDT, CURRENTDATE

## Programs Using This Table
- `zisdm0040`
- `zisdm0116`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CURRENTDATE` | DATS | 8 | 🔑 | Date |
| 3 | `CANTREADDEVICE` | NUMC | 5 |  | Number of Can't Read Devices |
| 4 | `CACDEVICE` | NUMC | 5 |  | Number of CAC devices |
