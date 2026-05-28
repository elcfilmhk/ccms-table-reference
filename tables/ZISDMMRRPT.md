# ZISDMMRRPT
**Description:** Customized table for Meter Reading Report
**Total Fields:** 7
**Key Fields:** MANDT, PCID, REPID, REPDATE, SEQNO, SOURCE_SYSTEM

## Programs Using This Table
- `zisdh0004`
- `zisdm0040`
- `zisdm0049`
- `zisdm0050`
- `zisdm0051`
- `zisdm0070`
- `zisdm0129`
- `zisdm0130`
- `zisdm0137`
- `zisdm0411`
- `zrdm_us_rep`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `PCID` | CHAR | 6 | 🔑 | Additional Identification Characteristic |
| 3 | `REPID` | CHAR | 8 | 🔑 | Parallel report |
| 4 | `REPDATE` | DATS | 8 | 🔑 | Date stamp |
| 5 | `SEQNO` | CHAR | 8 | 🔑 | Sequence number |
| 6 | `SOURCE_SYSTEM` | CHAR | 1 | 🔑 | Source System |
| 7 | `CONTENT` | CHAR | 255 |  | Context string |
