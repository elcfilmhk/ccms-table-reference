# ZFICAT0001
**Description:** SMIS: Payment Log Number Range
**Total Fields:** 4
**Key Fields:** MANDT, ZGRPID

## Programs Using This Table
- `zfiapc000`
- `zfiarc000`
- `zmmpri000`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ZGRPID` | CHAR | 4 | 🔑 | SMIS: FICA Payment Log Number Group |
| 3 | `ZIDNUM` | NUMC | 8 |  | SMIS: FICA Payment Log Current Number |
| 4 | `DEL` | CHAR | 1 |  | Deletion Indicator |
