# ZISDMGPBILESTACT
**Description:** Specify the system behavior for the group bill child account
**Total Fields:** 6
**Key Fields:** MANDT, TARIFTYP, READING_STATUS, MASTER_SUB_IND, CONSUMPTION

## Programs Using This Table
- `zisdm0156`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 3 | `READING_STATUS` | CHAR | 1 | 🔑 | Meter Reading Status |
| 4 | `MASTER_SUB_IND` | CHAR | 1 | 🔑 | Master-sub indicator |
| 5 | `CONSUMPTION` | NUMC | 12 | 🔑 | Consumption of the MRO |
| 6 | `ACTION` | CHAR | 1 |  | The action to be taken |
