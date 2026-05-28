# ZISDMFLAT
**Description:** To store the English and Chinese version of the Flat Type
**Total Fields:** 4
**Key Fields:** MANDT, ADDRNUMBER

## Programs Using This Table
- `zisdm0015`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ADDRNUMBER` | CHAR | 10 | 🔑 | Address number |
| 3 | `FLAT_TYPE_EN` | CHAR | 10 |  | The English version of the flat type |
| 4 | `FLAT_TYPE_CH` | CHAR | 10 |  | The Chinese version of the flat type |
