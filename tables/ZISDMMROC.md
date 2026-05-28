# ZISDMMROC
**Description:** Cust Table : Meter Reading Group and Operating Center
**Total Fields:** 3
**Key Fields:** MANDT, MRGROUP

## Programs Using This Table
- `zisbi0104`
- `zisdh0009`
- `zisdm0118`
- `zisdm0330`
- `zisdm0336`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MRGROUP` | CHAR | 2 | 🔑 | Meter Reading Group |
| 3 | `OPCENTER` | CHAR | 10 |  | Operating Center |
