# ZISCRMFCRREASGRP
**Description:** First Contact Resolution (FCR) - Reason group (Group Config)
**Total Fields:** 5
**Key Fields:** MANDT, FCR_REASON_GRP, FCR_STANDARD

## Programs Using This Table
- `ziscrm0002`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FCR_REASON_GRP` | CHAR | 3 | 🔑 | FCR Reason group |
| 3 | `FCR_STANDARD` | CHAR | 1 | 🔑 | FCR Standard |
| 4 | `FCR_PERIOD` | CHAR | 2 |  | FCR Period |
| 5 | `FCR_FREQUENCY` | INT1 | 3 |  | FCR Frequency |
