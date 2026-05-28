# ZISDM_MOL_FC_LOC
**Description:** Forecast Location Codes
**Total Fields:** 5
**Key Fields:** MANDT, FC_LOC_CODE

## Programs Using This Table
- `ziscrm0031`
- `zisdm0288`
- `zisdm0291`
- `zisdm0292`
- `zisdm0318`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FC_LOC_CODE` | CHAR | 8 | 🔑 | Location of Forecast |
| 3 | `FC_LOC_DESC` | CHAR | 80 |  | Text (80 Characters) |
| 4 | `ACTUAL_AREA_TEXT` | CHAR | 120 |  | Text (Length 120) |
| 5 | `DELETED` | CHAR | 1 |  | Deletion Indicator |
