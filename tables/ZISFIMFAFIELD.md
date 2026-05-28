# ZISFIMFAFIELD
**Description:** Table for dynamic selection screen
**Total Fields:** 9
**Key Fields:** MANDT, SCREEN, FIELD_NAME

## Programs Using This Table
- `zisfi0297`
- `zisfi0299`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `SCREEN` | NUMC | 2 | 🔑 | Sequence number |
| 3 | `FIELD_NAME` | CHAR | 80 | 🔑 | Field Name |
| 4 | `DESCRIPTION` | CHAR | 80 |  | Field Name |
| 5 | `INPUT_FIELD` | CHAR | 1 |  | General Flag |
| 6 | `ACTIVE` | CHAR | 1 |  | General Flag |
| 7 | `SEQUENCE` | NUMC | 2 |  | Sequence number |
| 8 | `UNIT` | CHAR | 12 |  | Unit |
| 9 | `FIELD_NAME_UNIT` | CHAR | 80 |  | Field Name |
