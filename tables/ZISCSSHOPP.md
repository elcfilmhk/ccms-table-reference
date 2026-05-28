# ZISCSSHOPP
**Description:** Map sevice order activity type to shop paper type
**Total Fields:** 5
**Key Fields:** MANDT, AUART, ILART, PM_APPL

## Programs Using This Table
- `zreprjt00`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AUART` | CHAR | 4 | 🔑 | Order Type |
| 3 | `ILART` | CHAR | 3 | 🔑 | Maintenance activity type |
| 4 | `PM_APPL` | CHAR | 1 | 🔑 | Application Area |
| 5 | `WORKPAPER` | CHAR | 4 |  | PM: Shop Paper |
