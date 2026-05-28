# ZISFILINKDEP
**Description:** DT Linking Deposit Level to Credit Period setting
**Total Fields:** 15
**Key Fields:** MANDT, VBSART, TARIFTYP, RUNDAT, RPT_GROUP

## Programs Using This Table
- `zisfi0200`
- `zisfi0201`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `VBSART` | CHAR | 8 | 🔑 | Type of premise |
| 3 | `TARIFTYP` | CHAR | 10 | 🔑 | Rate category |
| 4 | `RUNDAT` | DATS | 8 | 🔑 | Running Date |
| 5 | `RPT_GROUP` | CHAR | 20 | 🔑 | Reporting Group |
| 6 | `PYMT_FR` | CHAR | 4 |  | Payment Terms from |
| 7 | `PYMT_TO` | CHAR | 4 |  | Payment Terms to |
| 8 | `INSU_DEP_FR` | DEC | 9 |  | Insufficient SD amount from |
| 9 | `INSU_DEP_TO` | DEC | 9 |  | Insufficient SD amount to |
| 10 | `DUNS_FR` | NUMC | 5 |  | Dunning Score from |
| 11 | `DUNS_TO` | NUMC | 5 |  | Dunning Score to |
| 12 | `REVIEW_FEQ` | NUMC | 3 |  | Review frequency |
| 13 | `INV_CRT_FR` | DATS | 8 |  | From date |
| 14 | `INV_CRT_TO` | DATS | 8 |  | To date |
| 15 | `LOEVM` | CHAR | 1 |  | Deletion Indicator |
