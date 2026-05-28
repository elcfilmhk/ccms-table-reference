# ZISDMCCGRVPG
**Description:** Consistency Check Grp and Replacement Value Procedure Grp
**Total Fields:** 8
**Key Fields:** MANDT, TYPE, UNIT, TMINTERVAL, ZZNOBILLING, TOU_INDC

## Programs Using This Table
- `zisdm0127`
- `zisdm0279`
- `zised0001`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TYPE` | CHAR | 30 | 🔑 | Type |
| 3 | `UNIT` | CHAR | 10 | 🔑 | Unit |
| 4 | `TMINTERVAL` | CHAR | 3 | 🔑 | Time interval |
| 5 | `ZZNOBILLING` | CHAR | 1 | 🔑 | Not relevant to billing |
| 6 | `TOU_INDC` | CHAR | 1 | 🔑 | TOU Indicator |
| 7 | `SETTING` | CHAR | 10 |  | Setting |
| 8 | `DESCRIPTION` | CHAR | 50 |  | Description |
