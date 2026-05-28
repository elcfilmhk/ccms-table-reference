# ZISFITRMNL
**Description:** Terminal data
**Total Fields:** 5
**Key Fields:** MANDT, ZZSTORENUM, ZZTERMINALID

## Programs Using This Table
- `zisfi0003`
- `zisfi0280`
- `zisfi0323`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZSTORENUM` | CHAR | 3 | 🔑 | Store number |
| 3 | `ZZTERMINALID` | CHAR | 3 | 🔑 | Terminal ID |
| 4 | `ZZTERMINALDESC` | CHAR | 50 |  | Terminal Description |
| 5 | `ZZSTRGRP` | CHAR | 1 |  | Group by Store number |
