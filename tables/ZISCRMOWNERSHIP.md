# ZISCRMOWNERSHIP
**Description:** Table used for BA/CA ownership
**Total Fields:** 4
**Key Fields:** CLIENT, BRANCH

## Programs Using This Table
- `ziscrm_upd_zcont_acc`
- `ziscrm_upd_zcrbpowner`
- `zissd00100`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `CLIENT` | CLNT | 3 | 🔑 | Client |
| 2 | `BRANCH` | CHAR | 4 | 🔑 | BP ownership |
| 3 | `DESCRIPTION` | CHAR | 20 |  | Description |
| 4 | `TEAM_BP` | CHAR | 17 |  | Partner number |
