# ZISDMMTRRESEQ
**Description:** Enhance MRHS Meter Re-Sequence Process
**Total Fields:** 6
**Key Fields:** MANDT, ABLEINH, ACTUALMRDATE, SERNR

## Programs Using This Table
- `zisdm0103`
- `zisdm0165`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `ABLEINH` | CHAR | 8 | 🔑 | Meter Reading Unit |
| 3 | `ACTUALMRDATE` | DATS | 8 | 🔑 | Actually Reading Date |
| 4 | `SERNR` | CHAR | 18 | 🔑 | Serial Number |
| 5 | `POS_OLD` | CHAR | 6 |  | Old Position |
| 6 | `POS_NEW` | CHAR | 6 |  | New Position |
