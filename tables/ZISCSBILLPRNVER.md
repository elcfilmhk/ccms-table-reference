# ZISCSBILLPRNVER
**Description:** BT/LPT Bill Printing Version
**Total Fields:** 6
**Key Fields:** MANDT, VKONT, GPART

## Programs Using This Table
- `ziscs0211`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `GPART` | CHAR | 10 | 🔑 | Business Partner Number |
| 4 | `BILLPRNVER` | CHAR | 1 |  | BT/LPT Bill Printing Version |
| 5 | `LAST_USER` | CHAR | 12 |  | Last Changed By |
| 6 | `LAST_CHG` | DATS | 8 |  | Last Changed On |
