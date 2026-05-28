# ZISDMMRVILLAGE
**Description:** Village information of the meter reading route
**Total Fields:** 5
**Key Fields:** MANDT, MAINMRU

## Programs Using This Table
- `zisdm0351`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MAINMRU` | CHAR | 8 | 🔑 | Meter Reading Unit |
| 3 | `VILLAGEIND` | CHAR | 5 |  | The village indicator of the main MRU |
| 4 | `VILLAGENAME` | CHAR | 80 |  | The name of the Village |
| 5 | `VILLAGEDESC` | CHAR | 80 |  | The Description of the Village |
