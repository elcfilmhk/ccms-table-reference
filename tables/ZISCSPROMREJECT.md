# ZISCSPROMREJECT
**Description:** Promotion Management: Reject Reason
**Total Fields:** 4
**Key Fields:** MANDT, PROMONAME, PROMREJECT

## Programs Using This Table
- `ziscs0164`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PROMONAME` | CHAR | 10 | 🔑 | Promotion activity name |
| 3 | `PROMREJECT` | CHAR | 1 | 🔑 | Reject reason code |
| 4 | `PROMREJTXT` | CHAR | 30 |  | Reject reason description |
