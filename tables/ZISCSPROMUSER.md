# ZISCSPROMUSER
**Description:** The user ID eligible for a particular promotion
**Total Fields:** 3
**Key Fields:** MANDT, PROMONAME, PROMOUSER

## Programs Using This Table
- `zpromotion`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMONAME` | CHAR | 10 | 🔑 | Promotion activity name |
| 3 | `PROMOUSER` | CHAR | 12 | 🔑 | Responsible person user ID |
