# ZISDMCTGSTMI
**Description:** CT meter installed in GST account to generate MI order
**Total Fields:** 5
**Key Fields:** MANDT, PRIORITY

## Programs Using This Table
- `zisdm0069`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRIORITY` | NUMC | 4 | 🔑 | Priority |
| 3 | `GROES` | CHAR | 18 |  | Size/dimension |
| 4 | `INVNR` | CHAR | 25 |  | Primary Voltage |
| 5 | `PERCENTAGE` | DEC | 5 |  | Percentage |
