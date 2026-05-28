# ZISBIGBAC
**Description:** New format for CA
**Total Fields:** 5
**Key Fields:** MANDT, VKONT

## Programs Using This Table
- `zisbi0096`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VKONT` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
| 4 | `AEDAT` | DATS | 8 |  | Date of Last Change |
| 5 | `AENAM` | CHAR | 12 |  | Name of person who changed object |
