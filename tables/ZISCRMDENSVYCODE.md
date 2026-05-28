# ZISCRMDENSVYCODE
**Description:** Answer choices of Survey Questions
**Total Fields:** 5
**Key Fields:** MANDT, ITEM_NO, CODE

## Programs Using This Table
- `ziscrm0006`
- `ziscrm0007`
- `ziscrm0008`
- `ziscs0214`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ITEM_NO` | NUMC | 3 | 🔑 | Item Number |
| 3 | `CODE` | CHAR | 4 | 🔑 | Choice of Question / Survey |
| 4 | `DESC_ENG` | CHAR | 30 |  | Choice Code Description in English |
| 5 | `DESC_CHI` | CHAR | 30 |  | Choice Code Description in Chinese |
