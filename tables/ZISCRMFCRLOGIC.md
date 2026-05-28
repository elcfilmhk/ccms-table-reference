# ZISCRMFCRLOGIC
**Description:** First Contact Resolution (FCR) - Logic (Individual Config.)
**Total Fields:** 9
**Key Fields:** MANDT, ACTIVITY_GRP, ACTIVITY_SUB_CAT, FCR_STANDARD, FCR_REASON_GRP, FCR_MARK

## Programs Using This Table
- `ziscrm0002`
- `ziscrm0003`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACTIVITY_GRP` | CHAR | 25 | 🔑 | Activity group |
| 3 | `ACTIVITY_SUB_CAT` | CHAR | 40 | 🔑 | Activity sub category |
| 4 | `FCR_STANDARD` | CHAR | 1 | 🔑 | FCR Standard |
| 5 | `FCR_REASON_GRP` | CHAR | 3 | 🔑 | FCR Reason group |
| 6 | `FCR_MARK` | CHAR | 1 | 🔑 | FCR Mark |
| 7 | `FCR_MEASURE` | CHAR | 1 |  | FCR Measure |
| 8 | `FCR_PERIOD` | CHAR | 2 |  | FCR Period |
| 9 | `FCR_FREQUENCY` | INT1 | 3 |  | FCR Frequency |
