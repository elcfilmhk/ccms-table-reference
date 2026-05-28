# ZISDMADRCUSTGRP
**Description:** DR Customer Group
**Total Fields:** 3
**Key Fields:** MANDT, CUSTOMER_GROUP_CODE

## Programs Using This Table
- `zisdm0313_adr`
- `zisdm0356`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CUSTOMER_GROUP_CODE` | CHAR | 11 | 🔑 | Program ID |
| 3 | `DESCRIPTION` | CHAR | 100 |  | Group code Description |
