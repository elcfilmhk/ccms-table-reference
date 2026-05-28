# ZISDMINSTR
**Description:** Instruction Code Table
**Total Fields:** 4
**Key Fields:** MANDT, INSTRCODE

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`
- `zisdm0233`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `INSTRCODE` | CHAR | 2 | 🔑 | Instruction Code |
| 3 | `DESCRIPTION` | CHAR | 40 |  | Code Description |
| 4 | `FORCEIND` | CHAR | 1 |  | Force Indicator - Handheld will be beeped if flag is set |
