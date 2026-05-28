# ZISCSREMARKSHOW
**Description:** Define short text display attribute in CRM
**Total Fields:** 9
**Key Fields:** MANDT, TXTORIG, SHORT_TEXT

## Programs Using This Table
- `zaccount`
- `zpartner`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `TXTORIG` | CHAR | 2 | 🔑 | Text origin |
| 3 | `SHORT_TEXT` | CHAR | 70 | 🔑 | Short text |
| 4 | `PRIORITY` | CHAR | 1 |  | Priority |
| 5 | `COLOR` | CHAR | 2 |  | Color (Allowable color in Html definition) |
| 6 | `BOLD` | CHAR | 1 |  | Font Style: Bold |
| 7 | `ITALIC` | CHAR | 1 |  | Font Style: Italic |
| 8 | `UNDERLINE` | CHAR | 1 |  | Underline indicator |
| 9 | `CIC0_ISU` | CHAR | 1 |  | Show in CIC0 ISU |
