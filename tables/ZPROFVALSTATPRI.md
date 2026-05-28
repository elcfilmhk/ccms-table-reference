# ZPROFVALSTATPRI
**Description:** Profile Value Status Priority
**Total Fields:** 7
**Key Fields:** MANDT, PRIORITY_TYPE, PRIORITY

## Programs Using This Table
- `zisdm0382`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PRIORITY_TYPE` | CHAR | 2 | 🔑 | Priority Type |
| 3 | `PRIORITY` | NUMC | 2 | 🔑 | Priority |
| 4 | `INT_STATUS` | CHAR | 5 |  | Internal Status of a Measured Value in EDM |
| 5 | `STATUS_S` | CHAR | 1 |  | Profile Value Status in Short Form |
| 6 | `EXT_STATUS` | CHAR | 4 |  | External Status of a Measured Value in EDM |
| 7 | `TEXT` | CHAR | 30 |  | Text for External Status of Profile Values |
