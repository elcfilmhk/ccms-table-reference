# ZISCRMFCRRESULT
**Description:** First Contact Resolution (FCR) - Result
**Total Fields:** 5
**Key Fields:** MANDT, FCR_NO

## Programs Using This Table
- `ziscrm0001`
- `ziscrm0002`
- `ziscrm0003`
- `ziscrm0004`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `FCR_NO` | NUMC | 10 | 🔑 | First Contact Resolution (FCR) number |
| 3 | `RESULT_AGENT` | CHAR | 1 |  | FCR Result (Agent) |
| 4 | `RESULT_CHANNEL` | CHAR | 1 |  | FCR Result (Channel) |
| 5 | `RESULT_ACTIVITY` | CHAR | 1 |  | FCR Result (Activity) |
