# ZISDMEVINTSTATUS
**Description:** The status of the interval
**Total Fields:** 3
**Key Fields:** MANDT, STATUS

## Programs Using This Table
- `zisdm0219`
- `zisdm0220`
- `zisdm0224`
- `zisdm0225`
- `zisdm0226`
- `zisdm0227`
- `zisdm0228`
- `zisdm0230`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `STATUS` | CHAR | 1 | 🔑 | The status of the interval |
| 3 | `STATUS_DESC` | CHAR | 15 |  | The description of the status |
