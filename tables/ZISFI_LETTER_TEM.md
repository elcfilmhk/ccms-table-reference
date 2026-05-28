# ZISFI_LETTER_TEM
**Description:** Master Letter Template
**Total Fields:** 15
**Key Fields:** MANDT, LETTER_ID, TEMPLATE_ID

## Programs Using This Table
- `zisbi0224`
- `zisfi0038`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `LETTER_ID` | CHAR | 15 | 🔑 | Letter ID |
| 3 | `TEMPLATE_ID` | CHAR | 30 | 🔑 | Template ID |
| 4 | `LETTER_TEMPLATE` | CHAR | 50 |  | Letter Template Description |
| 5 | `EFFECTIVE_DATE` | DATS | 8 |  | Effective Date |
| 6 | `EXPIRY_DATE` | DATS | 8 |  | Expiry date |
| 7 | `APPROVED` | CHAR | 1 |  | Approved |
| 8 | `APPROVED_DATE` | DATS | 8 |  | Approved Date |
| 9 | `OUTSTANDING_BAL` | CURR | 13 |  | Outstanding Balance |
| 10 | `SAME_CUSTOMERS` | INT1 | 3 |  | No of Same customers |
| 11 | `CREATED_BY` | CHAR | 12 |  | Name of Person Who Created the Object |
| 12 | `CREATION_DATE` | DATS | 8 |  | Created On |
| 13 | `LAST_CHANGED_BY` | CHAR | 12 |  | Name of person who changed object |
| 14 | `LAST_CHANGED_DATE` | DATS | 8 |  | Date of Last Change |
| 15 | `PRIORITY` | INT1 | 3 |  | Priority |
