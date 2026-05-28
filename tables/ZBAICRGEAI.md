# ZBAICRGEAI
**Description:** Interface control - eAI related information
**Total Fields:** 5
**Key Fields:** MANDT, REPID, FUNCT

## Programs Using This Table
- `zbaicf002`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `REPID` | CHAR | 40 | 🔑 | ABAP Program: Current Master Program |
| 3 | `FUNCT` | CHAR | 4 | 🔑 | Interface control - function name |
| 4 | `CATEGORY` | CHAR | 1 |  | CISS/EAI |
| 5 | `ARCHIVE` | CHAR | 1 |  | Ind:Archiving flag |
