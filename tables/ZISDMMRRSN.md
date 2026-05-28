# ZISDMMRRSN
**Description:** Meter Reading Reason / Meter Reading Type mapping table
**Total Fields:** 3
**Key Fields:** MANDT, ZMRREASON

## Programs Using This Table
- `zisdh0001`
- `zisdm0025`
- `zisdm0152`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZMRREASON` | CHAR | 2 | 🔑 | Meter reading reason |
| 3 | `ZMRTYPE` | CHAR | 1 |  | The Meter Reading Type |
