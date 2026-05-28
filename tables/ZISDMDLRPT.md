# ZISDMDLRPT
**Description:** Customized table for Meter Reading Report
**Total Fields:** 6
**Key Fields:** MANDT, REPID, FUNCT, TYPE, REPDATE

## Programs Using This Table
- `zisdm0027`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 4 | `TYPE` | CHAR | 1 | 🔑 | Streetwise Download Report type |
| 5 | `REPDATE` | DATS | 8 | 🔑 | Date stamp |
| 6 | `CONTENT` | CHAR | 255 |  | Context string |
