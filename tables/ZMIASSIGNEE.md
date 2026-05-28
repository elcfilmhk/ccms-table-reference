# ZMIASSIGNEE
**Description:** Custom table to store the available assignee
**Total Fields:** 4
**Key Fields:** MANDT, STAFFID

## Programs Using This Table
- `ziscs0261`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `STAFFID` | CHAR | 12 | 🔑 | User Name |
| 3 | `OUTSTANDING` | NUMC | 3 |  | No. of outstanding cases |
| 4 | `STATUS` | CHAR | 1 |  | Status of the assignee (A-Available, L-Leave) |
