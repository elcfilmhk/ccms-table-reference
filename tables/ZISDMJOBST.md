# ZISDMJOBST
**Description:** Job Status Table
**Total Fields:** 3
**Key Fields:** MANDT, ZZJOBSTAT

## Programs Using This Table
- `zisdh0004`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0051`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZZJOBSTAT` | CHAR | 2 | 🔑 | Job Status of meter reading action |
| 3 | `ZZJOBDESC` | CHAR | 40 |  | Code Description |
