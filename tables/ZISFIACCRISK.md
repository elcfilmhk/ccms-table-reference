# ZISFIACCRISK
**Description:** High risk account class list
**Total Fields:** 6
**Key Fields:** MANDT, KTOKL, VALID_FROM, VALID_TO

## Programs Using This Table
- `zisfi0149`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `KTOKL` | CHAR | 4 | 🔑 | Account class |
| 3 | `VALID_FROM` | DATS | 8 | 🔑 | Account class validity start date |
| 4 | `VALID_TO` | DATS | 8 | 🔑 | Account class validity end date |
| 5 | `CREATED_ON` | DATS | 8 |  | Date on Which Record Was Created |
| 6 | `CHANGED_ON` | DATS | 8 |  | Date of Last Change |
