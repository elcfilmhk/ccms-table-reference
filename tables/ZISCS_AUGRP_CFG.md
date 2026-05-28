# ZISCS_AUGRP_CFG
**Description:** Configuration table for authorization group update
**Total Fields:** 6
**Key Fields:** MANDT, SEQ, BPKIND, AKLASSE, TARIFTYP

## Programs Using This Table
- `ziscs0488`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SEQ` | NUMC | 4 | 🔑 | Seq. No. |
| 3 | `BPKIND` | CHAR | 4 | 🔑 | Business Partner Type |
| 4 | `AKLASSE` | CHAR | 4 | 🔑 | Billing class |
| 5 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 6 | `BEGRU` | CHAR | 4 |  | Authorization Group |
