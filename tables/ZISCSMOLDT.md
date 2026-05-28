# ZISCSMOLDT
**Description:** Log table for MOL-DT upload
**Total Fields:** 6
**Key Fields:** MANDT, CA, CREATED_TMST, MESSAGE

## Programs Using This Table
- `ziscs0284`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CA` | CHAR | 12 | 🔑 | Contract Account Number |
| 3 | `CREATED_TMST` | CHAR | 14 | 🔑 | Created timestamp |
| 4 | `MESSAGE` | CHAR | 50 | 🔑 | Result of the upload process |
| 5 | `CREATED_BY` | CHAR | 20 |  | Created by |
| 6 | `STATUS` | CHAR | 1 |  | MOL for DT Creation Status |
