# ZISCSCONF_BLKOT
**Description:** Blackout Period Configuration Table
**Total Fields:** 6
**Key Fields:** MANDT, COMM_CHANNEL, SEQID

## Programs Using This Table
- `z_iscsget_blkout==============ft`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `COMM_CHANNEL` | CHAR | 1 | 🔑 | Communication Channel |
| 3 | `SEQID` | CHAR | 3 | 🔑 | Sequence Number like 010, 020 etc. |
| 4 | `BLACKOUT_FROM` | TIMS | 6 |  | Field of type TIMS |
| 5 | `BLACKOUT_TO` | TIMS | 6 |  | Field of type TIMS |
| 6 | `ACTIVE` | CHAR | 1 |  | Flag to mark if the blackout period is active or not |
