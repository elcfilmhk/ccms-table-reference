# ZISBIREASONGRP
**Description:** Reversal reason grouping
**Total Fields:** 4
**Key Fields:** MANDT, BCREASON

## Programs Using This Table
- `zisbi0014`
- `zisbi0014t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `BCREASON` | CHAR | 2 | 🔑 | Reason for Reversal |
| 3 | `FAULT_TYPE` | NUMC | 2 |  | Fault type |
| 4 | `REASON_GROUP` | NUMC | 2 |  | Reason group |
