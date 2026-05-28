# ZISCSEVER_CRMQ
**Description:** ISU Contract CRM-Entry Queue
**Total Fields:** 5
**Key Fields:** MANDT, CRM_OBJECT_ID, ERDAT, ERZEIT, ERNAM

## Programs Using This Table
- `ziscrm0050`

## Field Definitions

| # | Field | Type | Len | Key | Description |
|---|-------|------|-----|-----|-------------|
| 1 | `MANDT` | CLNT | 3 | 🔑 | Client |
| 2 | `CRM_OBJECT_ID` | CHAR | 10 | 🔑 | Transaction Number in CRM Document |
| 3 | `ERDAT` | DATS | 8 | 🔑 | Date on Which Record Was Created |
| 4 | `ERZEIT` | TIMS | 6 | 🔑 | Time, at Which Record Was Added |
| 5 | `ERNAM` | CHAR | 12 | 🔑 | Name of Person Who Created the Object |
