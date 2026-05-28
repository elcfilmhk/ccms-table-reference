# ZISDMEVREJSTATUS
**Description:** The status of rejected charging session
**Total Fields:** 3
**Key Fields:** MANDT, STATUS

## Programs Using This Table
- `zisdm0224`
- `zisdm0226`
- `zisdm0230`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `STATUS` | CHAR | 1 | 🔑 | Status of reject charging session |
| 3 | `STATUS_DESC` | CHAR | 30 |  | The description of the rejected session status |
