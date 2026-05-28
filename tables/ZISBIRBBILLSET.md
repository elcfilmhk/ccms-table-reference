# ZISBIRBBILLSET
**Description:** Random Bill Selection Report Bill Set Priority
**Total Fields:** 10
**Key Fields:** MANDT, ZINDEX, TARIFTYP, DESCRIPTION, CRITERIA

## Programs Using This Table
- `zisbi0270`
- `zisbi0270t`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZINDEX` | NUMC | 4 | 🔑 | Index |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate Category |
| 4 | `DESCRIPTION` | CHAR | 30 | 🔑 | Description |
| 5 | `CRITERIA` | CHAR | 30 | 🔑 | Criteria |
| 6 | `BILLTYPE` | CHAR | 2 |  | Bill Type |
| 7 | `ZSET` | CHAR | 1 |  | Bill Combination Set |
| 8 | `PRIORITY` | CHAR | 1 |  | Priority |
| 9 | `AMI` | CHAR | 1 |  | AMI |
| 10 | `FIT` | CHAR | 1 |  | FiT |
