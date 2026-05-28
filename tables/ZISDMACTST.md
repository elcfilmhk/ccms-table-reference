# ZISDMACTST
**Description:** Action Status
**Total Fields:** 3
**Key Fields:** MANDT, ACTIONSTATUS

## Programs Using This Table
- `zisdh0004`
- `zisdm0049`
- `zisdm0051`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ACTIONSTATUS` | CHAR | 2 | 🔑 | Status of Action to be taken |
| 3 | `DESCRIPTION` | CHAR | 40 |  | Code Description |
