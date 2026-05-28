# ZISDMMAP_AMCG
**Description:** Mapping of Current AMCG to Target AMCG
**Total Fields:** 5
**Key Fields:** MANDT, AMCG_DGRP, AAMCG_CAP_GRP

## Programs Using This Table
- `zisdm0273`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `AMCG_DGRP` | CHAR | 10 | 🔑 | AMCG Determination Group |
| 3 | `AAMCG_CAP_GRP` | NUMC | 4 | 🔑 | Actual AMCG Cap. Group |
| 4 | `TAMCG_CAP_GRP` | NUMC | 4 |  | Target AMCG Ca. Group |
| 5 | `PROCESS` | CHAR | 1 |  | Allocation / Deallocation |
