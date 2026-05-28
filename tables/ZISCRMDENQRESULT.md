# ZISCRMDENQRESULT
**Description:** Data Enrichment - CA's Survey Question's Result
**Total Fields:** 7
**Key Fields:** MANDT, GUID

## Programs Using This Table
- `ziscrm0006`
- `ziscrm0007`
- `ziscrm0008`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `GUID` | CHAR | 32 | 🔑 | Unique Global Identifier |
| 3 | `CA` | CHAR | 12 |  | Contract Account Number |
| 4 | `QUESTION_NO` | NUMC | 3 |  | Question number |
| 5 | `VALUE1` | CHAR | 4 |  | Answer for item 1 |
| 6 | `VALUE2` | CHAR | 4 |  | Answer for item 2 |
| 7 | `VALUE3` | CHAR | 30 |  | Answer for item 3 (Choice or Text) |
