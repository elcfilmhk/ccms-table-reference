# ZISEDFITREGGRP
**Description:** FiT Device Register group list
**Total Fields:** 5
**Key Fields:** MANDT, ZWGRUPPE, EFFDATE

## Programs Using This Table
- `zised0049`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZWGRUPPE` | CHAR | 8 | 🔑 | Register Group |
| 3 | `EFFDATE` | DATS | 8 | 🔑 | Effective start date |
| 4 | `ENDDATE` | DATS | 8 |  | Effective End Date |
| 5 | `ERNAM` | CHAR | 12 |  | Name of Person Who Created the Object |
