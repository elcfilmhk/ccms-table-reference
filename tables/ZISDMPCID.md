# ZISDMPCID
**Description:** Mapping for Streetwise PC ID
**Total Fields:** 8
**Key Fields:** MANDT, MRGROUP, READMETHOD

## Programs Using This Table
- `zisdh0002`
- `zisdm0027`
- `zisdm0082`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `MRGROUP` | CHAR | 2 | 🔑 | Meter Reading Group ( = MRU+2(2) ) |
| 3 | `READMETHOD` | CHAR | 2 | 🔑 | Reading Method |
| 4 | `APERIOD` | CHAR | 1 |  | Aperiodic File Indicator |
| 5 | `PCID` | CHAR | 1 |  | Streetwise PC ID |
| 6 | `DWNLFILE` | CHAR | 10 |  | Streetwise Download filename by PC ID |
| 7 | `UPLDFILE` | CHAR | 10 |  | Upload filename by PC ID |
| 8 | `APRDWNLFILE` | CHAR | 10 |  | Streetwise Download filename by PC ID |
